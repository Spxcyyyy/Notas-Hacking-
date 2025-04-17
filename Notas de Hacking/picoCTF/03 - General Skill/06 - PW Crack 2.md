#### Descripción :
	Can you crack the password to get the flag?Download the password checker [here](https://artifacts.picoctf.net/c/13/level2.py) and you'll need the encrypted [flag](https://artifacts.picoctf.net/c/13/level2.flag.txt.enc) in the same directory too.
#### Solución :
	Descargue los archivos dados, luego hice un nano al level2.py para encontrar la contraseña, en el codigo estaba esta cadena de caracteres 'chr(0x64) + chr(0x65) + chr(0x37) + chr(0x36)' el cual le pase a chatgpt para que me diera su equivalente,el resultado fue 'de76'

2025-03-18 02:16:24 (9.34 MB/s) - 'level2.flag.txt.enc' saved [31/31]

	Krykoso-picoctf@webshell:~$ ls    
	README.txt  level2.flag.txt.enc  level2.py
	Krykoso-picoctf@webshell:~$ python3 level2.py 
	Please enter correct password for flag: dasdas
	That password is incorrect
	Krykoso-picoctf@webshell:~$ nano level2.py
	Krykoso-picoctf@webshell:~$ python3 level2.py 
	Please enter correct password for flag: de76
	Welcome back... your flag, user:
			
			
			picoCTF{tr45h_51ng1ng_489dea9a}