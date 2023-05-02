# Find-the-Greatest-of-the-Two-Numbers-in-C

Find the Greatest of the two numbers in C
Given two integer inputs num1 and num2, the objective if to write a code to Find the Greatest of the Two Numbers in C.
 
Example
Input : num1 = 5 and num2 = 6
Output : 6
larger of two numbers
Find the Largest of the Two Numbers in C
Given two integer inputs num1 and num2, the objective if to write a code to Find the Greatest of the Two Numbers in C. To do so we simply check whether num1 is larger than num2 using C Language. Here are some of the Methods to solve the above mentioned Problem.

Method 1 : Using if – else Statements
Method 2 : Using Ternary Operator
We’ll discuss each of the above mentioned methods in the upcoming sections in detail. You can check C++, Java, Python codes for greatest of two numbers here

Method 1 : Using if – else Statements
 

Algorithm and Explanation
The algorithm and the Explanation for the above problem is mentioned below.
For two numbers num1 & num2

If num1 == num2
Print both are equal
Else if num1 > num2
Print num1 is greater
Else, num2 has to be the greater
Print num2 is greater
Let’s try and implement the algorithm in C Language.

C Code
Run

#include<stdio.h>

int main ()
{
  int num1, num2;
  num1=12,num2=13;

  if (num1 == num2)
    printf("both are equal");
  else if (num1 > num2) 
    printf("%d is greater", num1);
  else
    printf("%d is greater", num2);

  return 0;
}
Output
13 is greater
Related Pages
Sum of N natural numbers

Sum of numbers in a given range
 
Greatest of the Three numbers

Leap year or not

Prime number

While loop in C
Method 2 : Using Ternary Operator
Algorithm and Explanation
In this method, we’ll use the knowledge of Ternary Operator in C . The Algorithm for the above mentioned problem is given below.
For two numbers num1 & num2

If num1 == num2
Print both are equal
Else, use ternary operator (temp = num1 > num2? num1: num2)
Print temp value is greater
Let’s try and implement the above algorithm in C Language.

C Code
Run
#include <stdio.h>
int main ()
{
    int num1, num2, temp;
    
    num1=20,num2=30;
    if(num1 == num2)
        printf("Both are Equal\n");
    else{
        temp = num1 > num2? num1 : num2;
        printf("%d is largest",temp);
    }

  return 0;
}
Output
30 is greater
