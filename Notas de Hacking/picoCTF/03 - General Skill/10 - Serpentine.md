#### Descripción :
		

Find the flag in the Python script![Download Python script](https://artifacts.picoctf.net/c/37/serpentine.py)
#### Solución :
	descargue el archivo y le hice un nano, al ejecutarlo pude ver que haia una funcion que regresaba la flag, pero esta no estaba en las opciones del menu, modifique el codigo para que la llamara al momento de recibir una b como respuesta

		Krykoso-picoctf@webshell:~$ nano serpentine.py 
Krykoso-picoctf@webshell:~$ python3 serpentine.py 

    Y
  .-^-.
 /     \      .- ~ ~ -.
()     ()    /   _ _   `.                     _ _ _
 \_   _/    /  /     \   \                . ~  _ _  ~ .
   | |     /  /       \   \             .' .~       ~-. `.
   | |    /  /         )   )           /  /             `.`.
   \ \_ _/  /         /   /           /  /                `'
    \_ _ _.'         /   /           (  (
                    /   /             \  \
                   /   /               \  \
                  /   /                 )  )
                 (   (                 /  /
                  `.  `.             .'  /
                    `.   ~ - - - - ~   .'
                       ~ . _ _ _ _ . ~

Welcome to the serpentine encourager!


a) Print encouragement
b) Print flag
c) Quit

What would you like to do? (a/b/c) b
			picoCTF{7h3_r04d_l355_7r4v3l3d_8e47d128}