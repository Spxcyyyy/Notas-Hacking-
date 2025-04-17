
## Descripción :
	The Multiverse is within your grasp! Unfortunately, the server that contains the secrets of the multiverse is in a universe where keyboards only have numbers and (most) symbols.


## Solución :
Una vez que me conecte por ssh, en el shell no se podían usar comandos que tuvieran letras, por lo que tuve que usar 'caracteres comodin' o 'wildcards', primero para hacer coincidir directorios, donde encontré uno llamado 'flag.txt', despues intente encontrar y ejecutar el comando `base32`, el cual estaba oculto en un directorio con un nombre ofuscado, primero probe ejecutarlo directamente con `/???/????32`, lo cual falló porque era un directorio. Luego, se almacene el error  en una variable (`_1=\`/???/????32 2>&1``) depsues solo extraje la parte que importa del mensaje (`${_1:0:11}`), que en teoria contenía la ruta correcta del ejecutable base32, y se use esa ruta para intentar ejecutar el programa sobre un archivo también ubicado en una ruta oculta (`??????/????.???`). al final, logre ejecutar el comando y ontuve el contenido del archivo codificado en base32, que al decodificar esa cadena, se obtuvo la flag:` 
picoCTF{7h15_mu171v3r53_15_m4dn355_b0d5e855}

![[Pasted image 20250415191303.png]]


![[Pasted image 20250415190548.png]]

picoCTF{7h15_mu171v3r53_15_m4dn355_b0d5e855}
