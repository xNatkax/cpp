# cpp
Tasks from C++ made to practice more programming language topics.

**Fundamentals** - tasks:

**task-1.cpp**
The fiscal receipt contains the following information:
    the net unit price "a",
    the number of items purchased "x", and
    the amount of VAT given as a percentage "p".
Write a program that reads the above data from the keyboard,
and then calculates the net value of the purchased goods, the value of VAT and the gross value of the goods.
List the results of the calculations on the screen in the form of a simplified "fiscal receipt".

**task-2.cpp**
Write a program that reads an integer N and then calculates and prints to the screen the value of N! 
Note: factorial causes integer overflow very quickly. 
Check for which values of N the program outputs the correct result.

**task-3.cpp**
Calculating the value of a polynomial using Horner's formula. 
The polynomial of the third degree is written with the formula: W(x)=ax3+bx2+cx+d. 
Write a program that calculates the value of this polynomial using Horner's formula: W(x)=((ax+b)x+c)x+d.

**task-4.cpp**
The program draws a number 0≤X≤100. 
Write a function that guesses the value of X. In a loop we draw n∈[0,100]. 
If X=n we have guessed X, if not based on the values of X and n we limit the interval from which we draw the next n.

**task-5.cpp**
Caesar's cipher involves encrypting consecutive letters (the other characters are left unchanged). 
Each letter is turned into the k-th next letter in the alphabet (k is the cipher constant), whereby if one does not exist (we leave after 'z'), the countdown continues back from 'a'. 
The encryption is case sensitive. Write a function that encrypts a string given as an argument.

**task-6.cpp**
Find the area bounded by the Ox axis and the graph of the function sin(x) in the interval [a,b] using the Monte Carlo method.
Input data: a, b, N (number of points drawn).

**task-7.cpp**
Write a program that tabulates the cosine function over a given interval.
Input data: beginning of the interval, end of the interval, step (increment x). 
The table should contain 3 columns: 
  the value of the argument x, 
  the value of cos(x) calculated using the library function, and 
  the value of cos(x) calculated from Taylor series expansion.
