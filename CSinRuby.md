## Chapter 1 Exercises 

1) 

a. number_to_square = gets 
    number_squared = number_to_square * number_to_square 
    

b. base = gets
    exponent = gets
    result = base * u
    
2) 

a. 

for (n = 1, n <= 100; counter++)
if (n == 1)
	n =+ n;
else 
	n =+ n + 1 

b. 



3) word = "anna"
    if each character of word is equal to each character of word.reverse at the same index, the word is a palindrome. 
    

4) 
if (opening)
	enter opening
if (wall) 
 	left !wall ?  turn left and go : turn right and go
  

5) 

a. The figure represents an algorithm for returning the proper change to a customer. 

b. If change due (C) is more than or equal to a dollar, give the customer one dollar and subtract a dollar from change due. Look at change due again, if it is still greater than or equal to one dollar, repeat the first step. If it is less than a dollar, and is greater than or equal to one quarter, give the customer one quarter and subtract that quarter from C. Repeat until C is no longer greater than or equal to one penny. 

6)

The engineer's algorithm "exits prematurely." As long as all the houses are connected, the engineer's algorithm exits, meaning that there is a chance the algorithm will connect all the houses and stop looking before the cheapest route has been found. 

## Chapter 2 Exercises

1) Write 208 in binary and in ternary 

	128-64-32-16 8-4-2-1 	
Binary: 1101 0000 

	2187-729-243-81   27-9-3-1
Ternary: 


2
2) 
1000 0001 = 129
129 in octal is 101. 


3) 9, 511, 056 bytes

1 Gigabyte; or closer to 10 megabytes 

4) 

Rate of transfer = 1 000 000 bits per second 

720 * 600 pixels = 2160 * 1800 bytes = 3 888 000 bytes = 31 104 000 bits 

Transferring a single frame would take thirty two seconds. 

25 * 32 = 

778 seconds 


90 minutes = 3600 seconds  

There's no way someone is going to be able to stream this movie without experiencing jittery playback. In fact, there wouldn't be much playback to speak of. 


0 rem !to "build/for-loops.prg"
10 for i=5 to 20 step 5
13 print i
15 for j=200 to 205 step 1
20 print "  ";j
21 for k=1 to 2
22 print "    ";k
23 next k
25 next j
30 next i




0 rem !to "build/for-loops.prg"
10 s=1024
20 for i = 0 to 39
30 poke s+i,81
40 next i