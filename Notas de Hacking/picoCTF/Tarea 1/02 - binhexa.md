#### Descripción :
	How well can you perfom basic binary operations?
	Additional details will be available after  launching your challenge instance.

#### Solución :
Realize todas la operaciones binarias pedidas con ayida de chatGpt:

Krykoso-picoctf@webshell:~$ nc titan.picoctf.net 56125

Welcome to the Binary Challenge!"
Your task is to perform the unique operations in the given order and find the final result in hexadecimal that yields the flag.

Binary Number 1: 11110110
Binary Number 2: 00011101


Question 1/6:
Operation 1: '+'
Perform the operation on Binary Number 1&2.
Enter the binary result: 100010011
Correct!

Question 2/6:
Operation 2: '<<'
Perform a left shift of Binary Number 1 by 1 bits.
Enter the binary result: 11111000
Incorrect. Try again
Enter the binary result: 111110000
Incorrect. Try again
Enter the binary result: 111101100
Correct!

Question 3/6:
Operation 3: '|'
Perform the operation on Binary Number 1&2.
Enter the binary result: 11111111
Correct!

Question 4/6:
Operation 4: '*'
Perform the operation on Binary Number 1&2.
Enter the binary result: 1101111011110
Correct!

Question 5/6:
Operation 5: '&'
Perform the operation on Binary Number 1&2.
Enter the binary result: 00010100
Correct!

Question 6/6:
Operation 6: '>>'
Perform a right shift of Binary Number 2 by 1 bits .
Enter the binary result: 00101011  
Incorrect. Try again
Enter the binary result: 00001110  
Correct!

Enter the results of the last operation in hexadecimal: 14
Incorrect answer!

Enter the results of the last operation in hexadecimal: 0E 

Correct answer!
The flag is: picoCTF{b1tw^3se_0p3eR@tI0n_su33essFuL_675602ae}
