
## Descripción :
	Do you know how to use the web inspector?Start searching [here](http://titan.picoctf.net:55265/) to find the flag
## Solución :
Entro a las paginas y es un sitio con tre secciones, al examinar cada una veo que en about hay una clase con una texto cifrado, lo decodifico con cyberchef y obtengo la flag

```
INPUT:cGljb0NURnt3ZWJfc3VjYzNzc2Z1bGx5X2QzYzBkZWRfZjZmNmI3OGF9

RECIPE:From base64

OUTPUT: picoCTF{web_succ3ssfully_d3c0ded_f6f6b78a}
```