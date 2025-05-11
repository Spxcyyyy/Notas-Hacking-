
## Descripción :
	Use `srch_strings` from the sleuthkit and some terminal-fu to find a flag in this disk image: [dds1-alpine.flag.img.gz](https://mercury.picoctf.net/static/626ea9c275fbd02dd3451b81f9c5e249/dds1-alpine.flag.img.gz)
## Solución :
	Descargue el archivo y lo descomprimí, comprobe su tipo y era una imagen de disco, entonces usando el comando strings con grep obtuve la flag 


![[Pasted image 20250510235251.png]]



	picoCTF{f0r3ns1c4t0r_n30phyt3_a6f4cab5}
