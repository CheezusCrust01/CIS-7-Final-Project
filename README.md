# CIS-7-Final-Project
Team Hard Stuck College: Vigenere Cipher Decryption Final Project


Hector Avina
Janelle Hamoy 
Michael Hareu


Moreno Valley College
CIS-7: Discrete Structures
June 8, 2023



Abstract
Team Hardstuck College has been tasked to create a code that resembles the famous Vigenère cipher that can also handle decryption and encryption as well. 
The problem that we are solving in this project is that we need to: create a C++ program that encrypts and decrypts a message from the user. 
Test the program to verify that the output is accurate. Assess program limitations. Provide documentation that entails programming approaches for encryption and decryption. 
The solution that we are implementing for the project is of course writing a C++ program in the website compiler IDE replit. But to solve this problem we are going to be 
using modular arithmetic implemented in the code to encrypt/decrypt what the user inputs. To encrypt/decrypt user input, the program will create a new key to match the 
length and formatting of the message by accessing the key variable (a string) as an array. By accessing the message and key as an array, the encryption/decryption process 
is done incrementally. To encrypt/decrypt, the decimal value of the characters are manipulated through addition, subtraction, and with the modulo function. As well as to 
attempt to handle characters that are not included in the alphabet, the program will detect those invalid characters. If those characters are detected in the key, the program 
will prompt the user to change the detected character. However in the message the user would like to encrypt/decrypt, the invalid characters will just be skipped in the encrypting/decrypting process. 
Provide explanation of calculations and algorithm implementation.
An algorithm implementation that is being used for this code is the modulus operator, a slight example of the operator is,when 15 is divided by 4, and the remainder is 3.
Therefore, the expression "15 % 4" evaluates to 3. The program objectives are to gather user input for the intended key and message, properly encrypt the user message, 
as well as properly decrypt the user message. Other program objectives include handling non-alphabetic characters. The program begins with prompting the user with three 
options which are “Enter 1 for Encryption, Enter 2 for Decryption, Enter 3 to TERMINATE the program”. Option 1 is for encrypting a message that the user inputs, with their 
own key as well. Code gives the user their own encrypted message. Option 2 decrypts the message from option 1 based on what the user’s message as well as the key they used 
in order to successfully decrypt the message. Option 3 just terminates the program once they are done with the code and are satisfied with their encryptions/decryptions. 
The purpose of this program is to prompt the user with the options of either encrypting/decrypting their message and at the end terminating it. Modular Arithmetic as stated
before is being implemented in this C++ program. Which is  arithmetic that deals with whole numbers where the numbers are replaced by their remainders after division by a fixed number.
Some of the limitations of this program is that both the message and the key consist only of alphabetic characters and spacing. Non-alphabetic characters, numbers, symbols will 
be saved  in the output but not encrypted or decrypted. The program does not handle different character encodings or non-English characters. 






