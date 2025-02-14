Descripción :
	What does this `bDNhcm5fdGgzX3IwcDM1` mean? I think it has something to do with bases.

Solución :
- Usar cyberchef para resolverlo
```
INPUT: bDNhcm5fdGgzX3IwcDM1
RECIPE: Base64
OUTPUT: l3arn_th3_r0p35

picoCTF{l3arn_th3_r0p35}
```
Notas adicionales:  También se puede resolver preguntándole a la IA o con Python

Python:
```
>>> import base64
>>> base64.b64decode('bDNhcm5fdGgzX3IwcDM1')
b'l3arn_th3_r0p35'
>>
```
