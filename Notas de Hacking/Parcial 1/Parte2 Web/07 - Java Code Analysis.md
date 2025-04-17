## Descripción :
	BookShelf Pico, my premium online book-reading service.I believe that my website is super secure. I challenge you to prove me wrong by reading the 'Flag' book!

## Solución :
Primero analice el codigo donde en la carpeta services y archivo UserServices encontre que el usuario con acceso era 'Admin' y en la carpeta seguridad, archivo SecretGenerator estaba la firma de los JWT que era '1234', entonce sfui a la pagina JSON web Tokens y decodifique el código y construí el nuevo token conforme a lo que encontré, y como la firma para el usuario era 1 intente con el 2 y obtuve el codigo

![[Pasted image 20250416185729.png]]
	picoCTF{w34k_jwt_n0t_g00d_602ce414}