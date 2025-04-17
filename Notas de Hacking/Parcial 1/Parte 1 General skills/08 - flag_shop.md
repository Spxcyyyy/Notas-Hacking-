
## Descripción :
	There's a flag shop selling stuff, can you buy a flag? [Source](https://jupiter.challenges.picoctf.org/static/253c4651d852ac6342752ff222cf2a83/store.c). Connect with `nc jupiter.challenges.picoctf.org 9745`.
## Solución :
El reto me da un puerto al que acceder que es un tipo de tienda donde se tiene que comprar la flag pero no me da el saldo suficiente para comprarla, por lo que analizo el código, y veo que usa variables int en el precio y el saldo, por lo que puedo hacer un desbordamiento lo intento poniendo 999999999 en la opción 1 y obtuve la bandera ya que el costo de la bandera apareció negativo y en el código evalúa si el costo es menor a mi saldo


picoCTF{m0n3y_bag5_65d67a74}
