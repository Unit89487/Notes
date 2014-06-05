####Chapter 3 
######Core Programming Elements

*Gem of Wisdom*: plain text files are stored as a simple sequence of characters in memory. Non plain-text files are commonly called binary files. 

A **variable** is a piece of data attached to a name. In a computer, they refer to a location in memory.

	variable_name = value

The equals sign has a different meaning in programming than it does in Algebra. In programming, = means "assign the value of the Right Hand Side (RHS) to the variable on the Left Hand Side (LHS)." In Ruby, the code snippet

	y = x + 2
	
means "compute the value of x + 2 and store the result in y." In algebra, y = x + 2 simply explains a relationship between variables x and y. 

If a variable does not change, it is called a **constant**. By declaring constants, you can use variables throughout the entire program without having to re-declare or risk a typing error by repeatedly inputting the same data over and over again. 

Data types indicate the nature of the variable and the range of valid values for that variable. The possible data types are: 
- **Integer** Any natural number or its negative. A subset of the infinite mathematical integers.  
- **Float** a decimal number. 
- **String** one or more characters surrounded by quotes. 
- **Booleans** true or false. Sometimes referred to as flags. 



###### Basic Arithmetical Operators 

- **+** 
- **-**
- *   (multiplication)
- **/**
- **%**  (Modulus. Returns the remainder of a division problem. For example, you can determine if *n* is even if *n* % 2 = 0.)
- ** (power. i.e. 2 ** 8 returns 16 or 2 ** 10 returns 1024)


##### Chapter 3 Exercises 
1) integer + integer; float + integer; string + string; 

2) They are the same if the parantheses do not override the order of operations. 

3) In the first code snippet (1.0 * 5 / 2), the order of operations converts five to a float and then divides it by two. In the second snippet (5 / 2 * 1.0), five is divided by two, and the quotient is then converted a float. 

4) a: 4  b: 4.5

5) a: 1.5  b: 2

6) This line of code has not placed the variables to be added in parantheses. The result is a divsion of the final variable by 4, and the results addition to the other three variables. The solution is to place the four variables to be added in parantheses, overriding the order of operations' insistence on dividing first. 

7) Logic errors are errors in the programs logical construction. An example would be placing an instruction for a program to repeat itself in such a place that it reinitializes relevant variables before the program has had a chance to use them as input for another step. Another example would be instructing a for-loop to repeat itself in a range that ultimately proves too limited to complete a given task. Syntax errors are errors where a programming language's keyword has been misstyped, i.e. "put" instead of "puts" in Ruby. Or declaring a chain of variables using a colon instead of a semi-colon. 








