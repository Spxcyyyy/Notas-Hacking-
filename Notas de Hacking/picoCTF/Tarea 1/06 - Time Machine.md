#### Descripción :
	What was I last working on? I remember writing a note to help me remember...You can download the challenge files here:

- [challenge.zip](https://artifacts.picoctf.net/c_titan/162/challenge.zip)
#### Solución :
Luego de descargar y descomprimir la carpeta hago un cat al archivo message y despues miro con git log y aparece la bandera 

	Krykoso-picoctf@webshell:~/drop-in/drop-in$ ls
	challenge.zip  drop-in
	Krykoso-picoctf@webshell:~/drop-in/drop-in$ cd drop-in/
	Krykoso-picoctf@webshell:~/drop-in/drop-in/drop-in$ ls
	message.txt
	Krykoso-picoctf@webshell:~/drop-in/drop-in/drop-in$ cat message.txt 
	This is what I was working on, but I'd need to look at my commit history to know why...Krykoso-picoctf@webshell:~/drop-in/drop-in/drop-in$ git log

	[5]+  Stopped                 git log
	Krykoso-picoctf@webshell:~/drop-in/drop-in/drop-in$ 
	

	commit 712314f105348e295f8cadd7d7dc4e9fa871e9a2 (HEAD -> master)
Author: picoCTF <ops@picoctf.com>
Date:   Tue Mar 12 00:07:26 2024 +0000

	    picoCTF{t1m3m@ch1n3_e8c98b3a}
(END)