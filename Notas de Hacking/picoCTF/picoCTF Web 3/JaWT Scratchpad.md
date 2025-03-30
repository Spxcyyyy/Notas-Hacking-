## Descripción :
	Check the admin scratchpad! `https://jupiter.challenges.picoctf.org/problem/58210/` or http://jupiter.challenges.picoctf.org:58210

## Solución :
		Una vex dentro de la pagina luego de logearme accedi a las cookies y al jwt que la pagina arojaba, ahi fui a un decodificador para saber como era el json que genraba y ahi vi que el token no estaba firmado como secreto, en la parte de abajo venia una pista que me llevaba a la herramienta 'john', usando mi entorno virtual de kali que ya tenia esa herramienta descargada, registre el token dado en un archivo y prodeci a usar john con el diccionario rockyou descomprimido previamente en /usr/share/wordlists/, para saber con que firma fue firmado el toquen, lo que me arrojo fue la palabra 'ilovepico' por lo que usando la erramienta de codificacion de jwt firme el token con 'ilovepico' para que me generara un nuevo token con esa firma, despues en la pagina actualize usando ese nuevo jwt y me dio la siguiente flag 
![[Pasted image 20250330004420.png]]


	Flag : 
	picoCTF{jawt_was_just_what_you_thought_44c752f5}