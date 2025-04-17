#### Descripción :
	Can you crack the password to get the flag?Download the password checker [here](https://artifacts.picoctf.net/c/12/level1.py) and you'll need the encrypted [flag](https://artifacts.picoctf.net/c/12/level1.flag.txt.enc) in the same directory too.
#### Solución :
Descargue ambos archivos y hice un cat al archivo level1 y busque la contraseña en el codigo la cual era '8713', ejecute el programa e introduje esa contraseña:

	2025-03-18 01:48:55 (1.15 MB/s) - 'level1.flag.txt.enc' saved [30/30]

	Krykoso-picoctf@webshell:~$ ls
	level1.flag.txt.enc  level1.py
	Krykoso-picoctf@webshell:~$ nano level1.py
	Krykoso-picoctf@webshell:~$ python level1.py 
	Please enter correct password for flag: 8713
	Welcome back... your flag, user:
	
			picoCTF{545h_r1ng1ng_1b2fd683}

