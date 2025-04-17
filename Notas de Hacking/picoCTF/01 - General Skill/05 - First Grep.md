Descripción: 
	Can you find the flag in [file](https://jupiter.challenges.picoctf.org/static/515f19f3612bfd97cd3f0c0ba32bd864/file)? This would be really tedious to look through manually, something tells me there is a better way.

Solución:
- Descargar el archivo y hacer un filtro por la palabra pico en el archivo
```
Krykoso-picoctf@webshell:~$ wget https://jupiter.challenges.picoctf.org/static/515f19f3612bfd97cd3f0c0ba32bd864/file
--2025-02-14 06:27:35--  https://jupiter.challenges.picoctf.org/static/515f19f3612bfd97cd3f0c0ba32bd864/file
Resolving jupiter.challenges.picoctf.org (jupiter.challenges.picoctf.org)... 3.131.60.8
Connecting to jupiter.challenges.picoctf.org (jupiter.challenges.picoctf.org)|3.131.60.8|:443... connected.
HTTP request sent, awaiting response... 200 OK
Length: 14551 (14K) [application/octet-stream]
Saving to: 'file.1'

file.1                       100%[=============================================>]  14.21K  --.-KB/s    in 0s      

2025-02-14 06:27:35 (413 MB/s) - 'file.1' saved [14551/14551]

Krykoso-picoctf@webshell:~$ grep pico
^C
Krykoso-picoctf@webshell:~$ grep pico file
picoCTF{grep_is_good_to_find_things_5af9d829}
Krykoso-picoctf@webshell:~$ ^C
Krykoso-picoctf@webshell:~$ 
```
