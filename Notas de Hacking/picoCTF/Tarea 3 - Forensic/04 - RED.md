## Descripción :
		
	RED, RED, RED, REDDownload the image: [red.png](https://challenge-files.picoctf.net/c_verbal_sleep/831307718b34193b288dde31e557484876fb84978b5818e2627e453a54aa9ba6/red.png)
## Solución :
	Descargue la imagen y le hice un strings, en el texto habia habian letras en mayuscula que formaban check lsb, ya daba una pista de que hacer, por lo que use la herramienta zsteg --lsb y me proporciono una cadena codificada, la pase a cyberchef y obtuve la bandera



![[Pasted image 20250512180045.png]]

![[Pasted image 20250512180057.png]]


picoCTF{r3d_1s_th3_ult1m4t3_cur3_f0r_54dn355_}