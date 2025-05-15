## Descripción :
	Can you get the real meaning from this file.Download the file [here](https://artifacts.picoctf.net/c_titan/1/enc_flag).
## Solución :
```
Al hacerle cat al archivo, me dio una cadena codificada en base64, al decodificarla me volvio a dar otra pero entre comillas 
```

![[Pasted image 20250515131733.png]]
```
Despues decodifique la cadena que estaba entre comillas simples, esta me devolvio otra que estaba codificada en caesar por las llaves 
```


![[Pasted image 20250515131753.png]]

```
Decodifique esta cadena caesar y obtuve la bandera 
```

![[Pasted image 20250515131820.png]]

```
	picoCTF{caesar_d3cr9pt3d_ea60e00b}
```
