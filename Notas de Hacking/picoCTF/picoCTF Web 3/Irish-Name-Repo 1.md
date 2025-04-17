## Descripción :
	There is a website running at `https://jupiter.challenges.picoctf.org/problem/50009/` ([link](https://jupiter.challenges.picoctf.org/problem/50009/)) or http://jupiter.challenges.picoctf.org:50009. Do you think you can log us in? Try to see if you can login!

## Solución :
	Hacer una inyeccion sql basica al login del sitio web usando como usarname: admin y como password : ' or 1=1; para que la consulta sql regrese verdadero

	Flag : Your flag is: picoCTF{s0m3_SQL_fb3fe2ad}