## Descripción :

	Alright, enough of using my own encryption. Flask session cookies should be plenty secure! [server.py](https://mercury.picoctf.net/static/c135543530f7dc24c3a6ecaeb44a81b8/server.py) [http://mercury.picoctf.net:65344/](http://mercury.picoctf.net:65344/)

## Solución :
Entrar a la pagina dada y descargar el archivo que nos dan, al analizar el código vemos que usa una lista de palabras las cuales podemos usar para un ataque de fuerza bruta,
primero haciendo un entorno virtual de python con venv 
despues descargar la libreria de flask-unsign y pasarle la pagina y el archivo de cookies , y con curl -s hacer una solicitud https , como se meustra en la imagen y asi obtener la bandera:

![[Pasted image 20250406131109.png]]