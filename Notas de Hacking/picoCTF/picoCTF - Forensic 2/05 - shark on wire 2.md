udp.dstport == 22
## Descripción :
	We found this [packet capture](https://jupiter.challenges.picoctf.org/static/b506393b6f9d53b94011df000c534759/capture.pcap). Recover the flag that was pilfered from the network.
## Solución :
Al descargar el paquete era una imagen de trafico de red, donde al analizar detenida mente los udp en los stream 32 había un start y en el 60 un end, y donde cada uno de ellos tenia un puerto de origen distinto pero  el destino siempre era el 22, por lo que hice un script en python usando la libreria scapy para obtener la flag 

![[Pasted image 20250409223946.png]]

	picoCTF{p1LLf3r3d_data_v1a_st3g0}

