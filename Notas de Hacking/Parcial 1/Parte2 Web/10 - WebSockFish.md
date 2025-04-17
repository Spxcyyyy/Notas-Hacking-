## Descripción :
	Can you win in a convincing manner against this chess bot? He won't go easy on you!You can find the challenge [here](http://verbal-sleep.picoctf.net:64555/).
## Solución :
Cuando abri la pagina me llevo a u tablero de ajedrez, intente ganarle al pez pero no pude, entonces me puse a analizar su código para encontrar algo que me pudiera ayudar y encontré una función eval,   así que primero le envié por consola un mensaje con un numero grande con 'sendMessage'  pero el pez solo lo mostraba en la pagina , entonces volví a revisar el código y vi que envía esos valores para ver si el pescado estaba ganando ya que el pescado cuando eran valores grandes mostraba mensajes 'alardiantes' , entonces le envié un  mensaje con un numero negativo y obtuve la bandera 

![[Pasted image 20250416195603.png]]


picoCTF{c1i3nt_s1d3_w3b_s0ck3t5_1c70436a}