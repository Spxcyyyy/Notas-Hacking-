## Descripción: 
	Find the flag being held on this server to get ahead of the competition [http://mercury.picoctf.net:47967/](http://mercury.picoctf.net:47967/)
## Solución:

Hice uso del comando curl con el link dado con las opciones -I HEAD para que me mostrara los encabezados, ahí se encontraba la bandera 


	Krykoso-picoctf@webshell:~$ curl http://mercury.picoctf.net:47967/

	<!doctype html>
<html>
<head>
    <title>Red</title>
    <link rel="stylesheet" type="text/css" href="//maxcdn.bootstrapcdn.com/bootstrap/3.3.5/css/bootstrap.min.css">
        <style>body {background-color: red;}</style>
</head>
        <body>
                <div class="container">
                        <div class="row">
                           <div class="col-md-6">
                                <div class="panel panel-primary" style="margin-top:50px">
                                        <div class="panel-heading">
                                                <h3 class="panel-title" style="color:red">Red</h3>
                                        </div>
                                        <div class="panel-body">
                                                <form action="index.php" method="GET">
                                                        <input type="submit" value="Choose Red"/>
                                                </form>
                                        </div>
                                </div>
                           </div>
                           <div class="col-md-6">
                                <div class="panel panel-primary" style="margin-top:50px">
                                        <div class="panel-heading">
                                                <h3 class="panel-title" style="color:blue">Blue</h3>
                                        </div>
                                        <div class="panel-body">
	                                                <form action="index.php" method="POST">
                                                        <input type="submit" value="Choose Blue"/>
                                                </form>
                                        </div>
                                </div>
                           </div>
                        </div>
                </div>
        </body>
</html>
	Krykoso-picoctf@webshell:~$ - I HEAD curl http://mercury.picoctf.net:47967/
	-bash: -: command not found
	Krykoso-picoctf@webshell:~$ curl -I HEAD  http://mercury.picoctf.net:47967/
	curl: (6) Could not resolve host: HEAD
	HTTP/1.1 200 OK
	flag: picoCTF{r3j3ct_th3_du4l1ty_cca66bd3}
	Content-type: text/html; charset=UTF-8


	picoCTF{r3j3ct_th3_du4l1ty_cca66bd3}