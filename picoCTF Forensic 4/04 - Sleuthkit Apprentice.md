
## Descripción :
	
	Download this disk image and find the flag.Note: if you are using the webshell, download and extract the disk image into `/tmp` not your home directory.

- [Download compressed disk image](https://artifacts.picoctf.net/c/137/disk.flag.img.gz)
## Solución :
	Descargue la imagen de disco y lo descomprimí , usando la herramienta mmls para ver las particiones de la imagen de disco y fui viendo una a una, después con la herramienta fls para poder ver los directorios de la imagen de la ultima partición, entre a la carpeta root por que es donde se almacena la información  de usuario después busque en ella y en la carpeta 'my_folder '  había un archivo llamado flag.txt con icat para poder ver lo que había ahí, y estaba la flag 



![[Pasted image 20250511005811.png]]


picoCTF{by73_5urf3r_adac6cb4}
