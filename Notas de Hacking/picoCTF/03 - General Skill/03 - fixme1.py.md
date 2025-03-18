#### Descripción :
	Fix the syntax error in this Python script to print the flag.[Download Python script](https://artifacts.picoctf.net/c/26/fixme1.py)
#### Solución :
Luego de descargar el archivo  , busque el error de sangría en el código  que se encontraba en el ultimo print y lo ejecute

	Krykoso-picoctf@webshell:~$ nano fixme1.py 
    Krykoso-picoctf@webshell:~$ python 3 fixme1.py 
     python: can't open file '/home/Krykoso-picoctf/3': [Errno 2] No such file or directory
	Krykoso-picoctf@webshell:~$ python3 fixme1.py 
	That is correct! Here's your flag:
	
				picoCTF{1nd3nt1ty_cr1515_09ee727a}
