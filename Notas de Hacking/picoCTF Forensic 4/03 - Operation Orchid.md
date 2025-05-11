
## Descripción :
	
	Download this disk image and find the flag.Note: if you are using the webshell, download and extract the disk image into `/tmp` not your home directory.
- [Download compressed disk image](https://artifacts.picoctf.net/c/214/disk.flag.img.gz)
## Solución :
	Una vez que descargue y descomprimi la imagen monte el disco en el directorio /tmp/ , despues accedi a la carpeta root de la imagen, fallo por que no tenia permisos por lo que ejecute 'sudo su', ya dentro de root encontre un archivo llamado flag.tex.enc, le hice un cat y este estaba encriptado, por lo que accedi al .ash_history para ver los comandos usados y si habia alguna contraseña con la que se cifro el archivp, ahi vi que se habia usado openssl para cifrar el archivo y busque el comando para descifrarlo ,introduje la contraseña y le hice un cat al achivo de salida, aho rdtaba la flag



![[Pasted image 20250511003508.png]]


	picoCTF{h4un71ng_p457_1d02081e}                                                                             


