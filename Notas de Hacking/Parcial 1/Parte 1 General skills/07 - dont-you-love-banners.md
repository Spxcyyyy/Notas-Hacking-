
## Descripción :
	Can you abuse the banner?

Additional details will be available after launching your challenge instance.
## Solución :
Una vez que me conecte al primer puerto me dio la contraseña, por lo que procedí a entrar al segundo, en el segundo me pidio esa contraseña y me hizo 2 preguntas sobre la conferencias de ciber seguridad mas importante y el nombre de un hacker, después me dio conecto a la consola por lo que empecé a ver los archivos que había , no había nada importante en esa carpeta, por lo que  obte por ver las que había en root, ahí había un archivo llamado flag.txt donde en teoría estaba la bandera pero pues yo no tenia acceso a este, por lo que entre al archivo llamado script.py, en ese código una línea  que accedía a lo que había en el archivo banner de la Shell del usuario 'player', borre el banner y cree un enlace simbólico llamado banner en /home/player que apunta al archivo /root/flag.txt por lo que al desconectarme de la instancia y volver a acceder ahora el script abre y lee el /home/player/banner que ahora es el contenido de /root/flag.txt que es la flag 


![[Pasted image 20250415002514.png]]
 picoCTF{b4nn3r_gr4bb1n9_su((3sfu11y_218ef5d6}
