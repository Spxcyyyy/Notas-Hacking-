#### Descripción :
		Someone's commits seems to be preventing the program from working. Who is it?You can download the challenge files here:

- [challenge.zip](https://artifacts.picoctf.net/c_titan/157/challenge.zip)

#### Solución :

descargar el archivo zip, descomprimirlo y ejecutar el comando 'git log message.py' para descubrir la bandera 

	Krykoso-picoctf@webshell:~$ ls
	README.txt  challenge.zip  drop-in  serpentine.py
	Krykoso-picoctf@webshell:~$ cd drop-in/
	Krykoso-picoctf@webshell:~/drop-in$ git log message.py


		   picoCTF{@sk_th3_1nt3rn_cfca95b2}

	
	[1]+  Stopped                 git log message.py
	Krykoso-picoctf@webshell:~/drop-in$ 