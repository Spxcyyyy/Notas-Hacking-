
## Descripción :
	We have several pages hidden. Can you find the one with the flag?The website is running [here](http://saturn.picoctf.net:51258/).
## Solución :
Revisamos los href y vemos que hay una carpeta llamada secret, accedo a esta  y ahi otra llamada hidden , acceso y veo otra llamada superhidden

```

link : view-source:http://saturn.picoctf.net:51258/secret/hidden/superhidden/

<!DOCTYPE html>
<html>
  <head>
    <title></title>
    <link rel="stylesheet" href="mycss.css" />
  </head>

  <body>
    <h1>Finally. You found me. But can you see me</h1>
    <h3 class="flag">picoCTF{succ3ss_@h3n1c@10n_51b260fe}</h3>
  </body>
</html>

```


	picoCTF{succ3ss_@h3n1c@10n_51b260fe}