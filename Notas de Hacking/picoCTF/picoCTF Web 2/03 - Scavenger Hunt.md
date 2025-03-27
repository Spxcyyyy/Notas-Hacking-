## Descripción:
	There is some interesting information hidden around this site [http://mercury.picoctf.net:27393/](http://mercury.picoctf.net:27393/). Can you find it?
## Solución:
	Al inspeccionar el html de la pagina dada me dio la primera parte de la bandera ('picoCTF{t'). Después al inspeccionar la hoja de estilos encontré la segunda parte de la bandera (h4ts_4_l0), despues fui al archivo robots.txt donde se encontraba la tercera parte de la bandera (t_0f_pl4c).
	La cuarta parte se encontraba en el .htaccess que era accesible  (3s_2_lO0k) 
	por lo que  al finalizar busque en el apartado de .DS_Store
	donde estaba la parte final de la bandera (_d375c750}
)


	picoCTF{th4ts_4_l0t_0f_pl4c3s_2_lO0k_d375c750}



