Daniel Shortino
9 April 2023
# NASM-Project
CSM 145 32695 Assembly Project
Instructions:

In this assignment, we're going to create a program that reads command line instructions and builds a string accordingly. The commands to be processed are show below:

A: means add the next byte to the variable.

Example: Az means Add the letter z to the variable.

D: means delete all occurrences of the next byte from the variable

R: means replace all occurrences of the next byte in the variable with the byte after it.

Look below for sample input/output.

Input ends with a period.

Notice that after processing every command, the variable is displayed.

Pay attention to deleting letters that do not exist! Your code should handle that.

Your variable size is 100 bytes. So I won't create a string larger than 100 bytes 

Example Input
ALAOAAAY.

Output
L
LO
LOA
LOAY

Example Input
ALAOAAAYDAAAROZDX.

Output
L
LO
LOA
LOAY
LOY
LOYA
LZYA
