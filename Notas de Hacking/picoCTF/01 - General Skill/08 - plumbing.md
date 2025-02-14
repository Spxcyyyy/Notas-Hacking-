
Descripción:
	Sometimes you need to handle process data outside of a file. Can you find a way to keep the output from this program and search for the flag? Connect to `jupiter.challenges.picoctf.org 4427`.

Solución:
- Conectarse al servidor en el puerto especificado y trasladar los datos a un archivo de txt , despues leemos el documento datos y filtramos el texto con la palabra pico usando grip
```
Krykoso-picoctf@webshell:~$ nc jupiter.challenges.picoctf.org 4427 > datos
            
Krykoso-picoctf@webshell:~$ ls
README.txt  datos  flag  wget-log  wget-log.1  wget-log.2  wget-log.3
Krykoso-picoctf@webshell:~$ cat datos | grep pico 

picoCTF{digital_plumb3r_5ea1fbd7}
```

Notas Adicionales:
	