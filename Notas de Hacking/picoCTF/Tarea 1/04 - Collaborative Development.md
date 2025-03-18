#### Descripción :
	my team has been working very hard on new features for our flag printing program! I wonder how they'll work together?You can download the challenge files here:
- [challenge.zip](https://artifacts.picoctf.net/c_titan/179/challenge.zip)
#### Solución :
Luego de descargar y descomprimir el archivo habia un archivo .py que tenia parte de la bandera, tuve que ir cambiando de rama para encontrar cada una de las partes de la bandera (3 partes)

	Krykoso-picoctf@webshell:~$ ls
	README.txt  challenge.zip  drop-in
	Krykoso-picoctf@webshell:~$ rm -rf challenge.zip 
	Krykoso-picoctf@webshell:~$ cd drop-in/
	Krykoso-picoctf@webshell:~/drop-in$ ls
	flag.py
		Krykoso-picoctf@webshell:~/drop-in$ python3 flag.py 
	Printing the flag...
	Krykoso-picoctf@webshell:~/drop-in$ git branch -a


	Krykoso-picoctf@webshell:~/drop-in$ git branch 'feature/part-1'
	fatal: A branch named 'feature/part-1' already exists.
	Krykoso-picoctf@webshell:~/drop-in$ git checkout 'feature/part-1'
	Switched to branch 'feature/part-1'
	Krykoso-picoctf@webshell:~/drop-in$ flag.py
	-bash: flag.py: command not found
	Krykoso-picoctf@webshell:~/drop-in$ cat flag.py
	print("Printing the flag...")
	print("picoCTF{t3@mw0rk_", end='')Krykoso-picoctf@webshell:~/drop-in$ git checkout 'feature/part-2'
	Switched to branch 'feature/part-2'
	Krykoso-picoctf@webshell:~/drop-in$ cat flag.py
print("Printing the flag...")

	print("m@k3s_th3_dr3@m_", end='')Krykoso-picoctf@webshell:~/drop-in$ git checkout 'feature/part-3'
	Switched to branch 'feature/part-3'
	Krykoso-picoctf@webshell:~/drop-in$ cat flag.py
	print("Printing the flag...")

	print("w0rk_798f9981}")
	Krykoso-picoctf@webshell:~/drop-in$ 



picoCTF{t3@mw0rk_m@k3s_th3_dr3@m_w0rk_798f9981}