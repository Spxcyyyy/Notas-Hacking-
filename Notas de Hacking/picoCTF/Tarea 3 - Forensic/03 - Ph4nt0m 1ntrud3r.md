## Descripción :
	A digital ghost has breached my defenses, and my sensitive data has been stolen! 😱💻 Your mission is to uncover how this phantom intruder infiltrated my system and retrieve the hidden flag.To solve this challenge, you'll need to analyze the provided PCAP file and track down the attack method. The attacker has cleverly concealed his moves in well timely manner. Dive into the network traffic, apply the right filters and show off your forensic prowess and unmask the digital intruder!Find the PCAP file here [Network Traffic PCAP file](https://challenge-files.picoctf.net/c_verbal_sleep/3fe089c41615b9413666bedca922e07bf6ad8894a3dabd2737735143ad2396cf/myNetworkTraffic.pcap) and try to get the flag.
## Solución :
	Abri el archivo de paquetes con wireshark , vi que algunos paquetes tenian mayor longitud que otos,  entonces los filtre por la longitud 12 o 4, y despues los ordene por tiempo entonces los mande a cyberchef y obtuve la bandera



![[Pasted image 20250512174750.png]]


	picoCTF{1t_w4snt_th4t_34sy_tbh_4r_966d0bfb}