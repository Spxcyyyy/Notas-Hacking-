#### Descripción :
		Can you crack the password to get the flag?Download the password checker [here](https://artifacts.picoctf.net/c/17/level3.py) and you'll need the encrypted [flag](https://artifacts.picoctf.net/c/17/level3.flag.txt.enc) and the [hash](https://artifacts.picoctf.net/c/17/level3.hash.bin) in the same directory too.There are 7 potential passwords with 1 being correct. You can find these by examining the password checker script.
#### Solución :
	descargie los 3 archivos que me daban y al hace un nano al level3, vi que habia una lista de posibles contraseñas, introduje una a una, hasta la correcta, y el programa arrojo la flag:

	Krykoso-picoctf@webshell:~$ python3 level3.py 
	Please enter correct password for flag: f09e
	That password is incorrect
	Krykoso-picoctf@webshell:~$ python3 level3.py 
	Please enter correct password for flag: 4dcf
	That password is incorrect
	Krykoso-picoctf@webshell:~$ python3 level3.py 
	Please enter correct password for flag: 87ab
	Welcome back... your flag, user:

			picoCTF{m45h_fl1ng1ng_cd6ed2eb}