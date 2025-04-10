
## Descripción :
	Decode this [message](https://jupiter.challenges.picoctf.org/static/14393e18d98fedbaedbc28896d7ef31a/message.wav) from the moon.

## Solución :
	Descargue el archivo , despues vi el tipo de archivo que era, lo abri y era un audio, por que le aplique un strings pero no habia nada ahi, posterior a ello busque un decodificador de audio de sstv por que por su tipo era como asi transmitian imagenes, encontre uno github y lo puse a analizar el audio y me dio la siguiente imagen donde se encontraba la bandera :
	
	 picoCTF{beep_boop_im_in_space}
 
![[Pasted image 20250409202358.png]]