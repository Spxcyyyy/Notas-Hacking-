
## Descripción :
	Download this disk image, find the key and log into the remote machine.Note: if you are using the webshell, download and extract the disk image into `/tmp` not your home directory.

Additional details will be available after launching your challenge instance.
## Solución :
	Descargue primero el archivo comprimido y al descomprimirlo vi que era una imagen de disco, usando la herramienta mmls para ver las particiones de la imagen de disco, despues con la herramienta fls para poder ver los directorios de la imagen, entre a la carpeta root por que es donde se almacena la informacion de ssh, despues con icat para poder ver la llave privada, la movi a un archivo en disco y ejecute el comando para conectarme por ssh, liste los archivos y le hice cat a uno llamado flag  

![[Pasted image 20250511001015.png]]


	picoCTF{k3y_5l3u7h_339601ed|}