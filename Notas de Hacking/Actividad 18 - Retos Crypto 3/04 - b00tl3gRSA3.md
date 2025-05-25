## Descripción :
	In RSA d is a lot bigger than e, why don't we use d to encrypt instead of e? Connect with `nc jupiter.challenges.picoctf.org 19566`.

## Solución :
```

No podía resolver el descifrado de la manera tradicional, por una hint me daba a entender que tenia que buscar D,  me puse a investigar y lo podía obtener sacando la factorización de N , usa una herramienta para factorizar enteros grandes y obtuve el totient, se la pase a solver rsa y obtuve la bandera 
```

![[Pasted image 20250524192940.png]]

![[Pasted image 20250524192950.png]]

picoCTF{too_many_fact0rs_0731311}