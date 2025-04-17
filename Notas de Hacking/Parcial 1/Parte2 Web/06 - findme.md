## Descripción :
		Help us test the form by submiting the username as `test` and password as `test!`

.
## Solución :
Una vez entre a la pagina y haya iniciado sesion pues no pasaba nada, pero una pista hablaba de las redirecciones por lo que use burp para ver si es que había redireccionamiento, lo cual vi que era así , y en cada uno de los redireccionamientos había algunas palabras codificadas base64 por lo que use cyberchef para decodificarlo 

![[Pasted image 20250416182859.png]]


![[Pasted image 20250416182921.png]]


picoCTF{proxies_all_the_way_01e748db}