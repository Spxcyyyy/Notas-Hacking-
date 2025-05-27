
## Descripción :
	Can you get the flag?Go to this [website](http://saturn.picoctf.net:51447/) and see what you can discover.
## Solución :
Nos logueamos y al verificar el js podemos ver que en el código verifica comparando con la contraseña real y el usuario:

```
  
function checkPassword(username, password)
{
  if( username === 'admin' && password === 'strongPassword098765' )
  {
    return true;
  }
  else
  {
    return false;
  }
}
```
y al logearnos nos da la contraseña
	picoCTF{j5_15_7r4n5p4r3n7_a8788e61}






picoCTF{gr4d3_A_c00k13_65fd1e1a}