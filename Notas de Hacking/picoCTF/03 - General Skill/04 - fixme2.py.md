#### Descripción :
	Fix the syntax error in the Python script to print the flag.[Download Python script](https://artifacts.picoctf.net/c/4/fixme2.py)
#### Solución :
Luego de descargar el archivo, lo ejecute para ver que tipo   de error era y en que linea estaba, era una asignacion con un solo = en lugar de dos, lo corregi y lo volvi a ejecutar

	2025-03-18 01:41:43 (654 MB/s) - 'fixme2.py' saved [1029/1029]

	Krykoso-picoctf@webshell:~$ python3 fixme2.py 
	  File "/home/Krykoso-picoctf/fixme2.py", line 22
    if flag = "":
       ^^^^^^^^^
	SyntaxError: invalid syntax. Maybe you meant '==' or ':=' instead of '='?
	Krykoso-picoctf@webshell:~$ nano fixme2.py 
	Krykoso-picoctf@webshell:~$ python3 fixme2.py 
	That is correct! Here's your flag:


			 picoCTF{3qu4l1ty_n0t_4551gnm3nt_e8814d03}