
## Descripción :
	Reception of Special has been cool to say the least. That's why we made an exclusive version of Special, called Secure Comprehensive Interface for Affecting Linux Empirically Rad, or just 'Specialer'. With Specialer, we really tried to remove the distractions from using a shell. Yes, we took out spell checker because of everybody's complaining. But we think you will be excited about our new, reduced feature set for keeping you focused on what needs it the most. Please start an instance to test your very own copy of Specialer.

Additional details will be available after launching your challenge instance.

## Solución :
Al conectarme al servidor vi que no se podían usar comandos como ls, así que use help para ver que tipo de comandos había disponibles, entonces vi que echo estaba disponible y despues usarlo para ver los directorios estaban ocultos  

![[Pasted image 20250415192122.png]]
después investigando encontré el comando  echo "$(file.txt)"
para leer archivos a falta de muchos comandos de lectura y probé con varias combinaciones que usan los 'magos', hasta que di con la flag:
picoCTF{y0u_d0n7_4ppr3c1473_wh47_w3r3_d01ng_h3r3_38f5cc78}

![[Pasted image 20250415193634.png]]



