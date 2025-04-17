
## Descripción

Can you convert the number 42 (base 10) to binary (base 2)?

Solución
- Usar la funcion bin de python para convertir el numero decimal a binario
```
Krykoso-picoctf@webshell:~$ python3
Python 3.10.12 (main, Sep 11 2024, 15:47:36) [GCC 11.4.0] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> bin(42)[2:]
'101010'
```

picoFlag{101010}

Notas Adicionales : Tambien se puede resolver con cyberchef conviertiendo a ascii y despues a binario