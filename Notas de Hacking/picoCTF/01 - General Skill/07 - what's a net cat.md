Descripción:
	Using netcat (nc) is going to be pretty important. Can you connect to `jupiter.challenges.picoctf.org` at port `64287` to get the flag?
	
Solución: 
- usar el comando nc para conectarse al servidor en el puerto especificado 
```
Krykoso-picoctf@webshell:~$ nc jupiter.challenges.picoctf.org
nc: missing port number
Krykoso-picoctf@webshell:~$ nc jupiter.challenges.picoctf.org 64287
You're on your way to becoming the net cat master

picoCTF{nEtCat_Mast3ry_284be8f7}
```
