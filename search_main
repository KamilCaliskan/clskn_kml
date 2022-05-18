# Search for lines that start with From and a character
# followed by a two digit number between 00 and 99 followed by ':'
# Then print the number if it is greater than zero

import re

book=open('hemingway.txt')
for line in book:
    line=line.rstrip()
    A=re.findall('^From.*([2-8][3-8]):', line)
    if len(A) > 0:
 print(A)
 
    

