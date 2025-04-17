#### Descripción :
		Using a Secure Shell (SSH) is going to be pretty important.
	Additional details will be available after launching your challenge instance.
#### Solución :
	Me conecte mediante ssh a con los datos dados de picoCTF y me arrojo la bandera

	Krykoso-picoctf@webshell:~$ ssh ctf-player@titan.picoctf.net -p 49630
	The authenticity of host '[titan.picoctf.net]:49630 ([3.139.174.234]:49630)' can't be established.
	ED25519 key fingerprint is SHA256:4S9EbTSSRZm32I+cdM5TyzthpQryv5kudRP9PIKT7XQ.
	This key is not known by any other names
	Are you sure you want to continue connecting (yes/no/[fingerprint])? y
	Please type 'yes', 'no' or the fingerprint: y
	Please type 'yes', 'no' or the fingerprint: yes
	Warning: Permanently added '[titan.picoctf.net]:49630' (ED25519) to the list of known hosts.
	ctf-player@titan.picoctf.net's password: 
	Welcome ctf-player, here's your flag: picoCTF{s3cur3_c0nn3ct10n_8306c99d}
	Connection to titan.picoctf.net closed.
	Krykoso-picoctf@webshell:~$ 
	

				picoCTF{s3cur3_c0nn3ct10n_8306c99d}