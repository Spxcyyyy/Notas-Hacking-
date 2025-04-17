
## Descripción :
	Python scripts are invoked kind of like programs in the Terminal... Can you run [this Python script](https://mercury.picoctf.net/static/8e33ede04d02f3765b8c6a6e24d72733/ende.py) using [this password](https://mercury.picoctf.net/static/8e33ede04d02f3765b8c6a6e24d72733/pw.txt) to get [the flag](https://mercury.picoctf.net/static/8e33ede04d02f3765b8c6a6e24d72733/flag.txt.en)?

## Solución :
	Me dieron 3  archivos, al intentar correr  el programa me decia que necesitaba usar algun parametro, por lo que anlice el codigo y usaba los  -e/-d para cifrar o descifrar, por lo que lo corri usando el archivo flag.txt.en y use la contraseña dada en pw
	
![[Pasted image 20250414205658.png]]


	picoCTF{4p0110_1n_7h3_h0us3_aa821c16}