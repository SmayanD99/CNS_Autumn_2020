<!---
Cryptography and Network Security(CS60065) - Autumn 2020
Programming Assignment 2 : Dictionary-based attack to crack passwords using JTR

Smayan Das
18CS30011

-->
# How to Run:
1) Open up Terminal/Command Prompt and cd into the directory the unzipped folder is.
2) Type Command: `python main.py` to reproduce the dictionary.txt file
3) JTR Commands to Crack Password: 
	
	`john --wordlist=dictionary.txt shadow_file_1`
  
	`john --wordlist=dictionary.txt shadow_file_2`
  
	`john --wordlist=dictionary.txt shadow_file_3`

4) To show the cracked passwords from the john.pot file:
	
	`john --show shadow_file_1`
  
	`john --show shadow_file_2`
  
	`john --show shadow_file_3`
