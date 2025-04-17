
## Descripción :
	The Rust saga continues? I ask you, can I borrow that, pleeeeeaaaasseeeee?Download the Rust code [here](https://challenge-files.picoctf.net/c_verbal_sleep/babfbee79718a6363826ba86300173ffde6d81577e9dd07d4130c53a7eecf6c3/fixme2.tar.gz).
## Solución :
Descargue y descomprimí el archivo dado, además en la pista venia documentación para variables mutables, el código no se podía compilar ya que la función decrypt esperaba una variable mutable  y no estaba declarada de esa forma ni se usaba como si fuera mutable, una vez agregados los 'mut', el código compilo correctamente y al ejecutar el programa obtuve la bandera 

![[Pasted image 20250414234739.png]]
	picoCTF{4r3_y0u_h4v1n5_fun_y31?}
