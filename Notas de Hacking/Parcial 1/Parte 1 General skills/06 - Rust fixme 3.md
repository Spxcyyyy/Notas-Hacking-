
## Descripción :
	Have you heard of Rust? Fix the syntax errors in this Rust file to print the flag!Download the Rust code [here](https://challenge-files.picoctf.net/c_verbal_sleep/dcdaf491b35c1d0f5075e9583edbbb7aaea1dffb6ad32bc000e4d87b5200ff7b/fixme3.tar.gz).
## Solución :
Descargue y descomprimí el archivo dado, al ejecutar me dio un  error de 'unsafe funtion' investigando vi que es una función fuera de un bloque, abrí el código y note que la llave de apertura y de cierre estaban 'comentadas' por ello el programa no compilaba, al borrar el cometario y dejar solo las llaves el programa compilo y al ejecutarlo obtuve la bandera  


![[Pasted image 20250414235619.png]]


	picoCTF{n0w_y0uv3_f1x3d_1h3m_411}
