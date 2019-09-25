# Java-Practice-Problems
This repository will contain simple core java practice problems
Practice Program
### Output Based:
1. Write a Program to display “Hello World” on the output screen.

2. Write a Program to display “Welcome to Java 12” on the output screen.

  		Output: Welcome to Java 12

3. Write a Program to display “Good Evening, Welcome to Programming” on the output screen.

  		Output: 	Good Evening,
            		Welcome to  Programming
            
4. Write a Program to print “enter an integer” on the output screen.

    	Output: enter an integer
    
5. Write a Program to print “hello world!!!!” on the output screen.

    	Output: hello world!!!!
    
6. Write a Program to print “enter your name” on the output screen.

    	Output: enter your name

### Variable Declaration, initialization & displaying value on the output screen
1. Write a Program to declare and initialize two variable of type integer and print there value on the output screen.
  	Hint : 	
  	int input1 = 20;
  	int input2 = 30;
	
  	Output:	input1 = 20;

  	input2 = 30;
    
2. Write a Program to declare variables of all 8 primitive type, initialize and print them on output screen.

3. Write a Program to solve the following expression:

      2 + 3 – 5 *2 /5; 
      
      store the result in a variable and print it on the output screen.
   
4. Write a Program to solve the expression :

      22 / 7 ; 
      
      store the result in a variable and print it on the output screen.
      
5. Write a Program to solve the expression :

      23 % 10 ; 
      
      store the result in a variable and print it on the output screen.
      
6. Write a Program to declare and initialize two double type variable. Print the result of addition of these variables on the output screen

      Hint: double input1 = 3.14;
      
      double input2 = 5.0;
      
      Output :
      
      the sum of two variables = 8.14
      
      
7. Write a Program to solve the expression :

      -2 % 5 ;
      
      store the result in a variable and print it on the output screen.
      
8. Write a Program to solve the expression :

      -2 % -5 ; 
      
      store the result in a variable and print it on the output screen.
      
9. Write a Program to solve the expression :

      2 % -5 ; 
      store the result in a variable and print it on the output screen.
10. Write a Program to solve the expression :

      23 / 10 ;
      store the result in a variable and print it on the output screen.
      
11. Write a Program to solve the expression :

      23.0 / 10 ; 
      
      store the result in a variable and print it on the output screen.
      
12. Write a Program to solve the expression :

      23 / 10.0 ; 
      
      store the result in a variable and print it on the output screen.
      
13. Write a Program to declare variable to store your name (String name), mobile no and email (String email).

Hint : use reference variable of String class for name and email.
``` java
String name = “Ravi”;
String email = “ravi@gla.ac.in”;
```
### User Input using Scanner class
1. Write a Program to accept two integers from user, perform addition on them and display the result on the output screen.

2. Write a Program to accept name form the user and print welcome message with user name.
Input : Ravi
output : Welcome Ravi

3. Write a Program to declare variables of all 8 primitive type, initialize them by taking value from user and print them on output screen.

Hint: Scanner class doesn't provide direct method for character input, to get character input use the following code;
``` java
Scanner sc = new Scanner(System.in);
char input = sc.next().charAt(0);
```
4. Write a Program to accept name, age, gender form user and print them on output screen.

5. Write a Program to accept two numbers from user and print the result of division of two number on the output screen.
Input : 10 & 0
Output : check the output for given input.

6. Write a Program to accept first name, middle name & last name form user and print them on output screen.

### Conditional Statement & Iterative Statements
1. Write a Program to accept two numbers from user and print the greatest of them on output screen.

2. Write a Program to accept three numbers from user and print the smallest of the three on output screen.

3. Write a Program to accept a number from user and check whether number is even or odd. For even number print number is even and for odd number print number is odd.

4. Write a Program to accept a number from user and check whether it is divisible by 5. If number is divisible by 5 print Number is divisible by 5 else print number is not divisible by 5.

5. Write a Program to accept a number form user and print number of digits in the number.

6. Write a Program to accept a number form user and print all its digits.

7. Write a Program to accept a digit from user and print it in words.

Input = 7
output = seven

8. Write a Program to accept a number form user and print all its digits in word.

Input = 4532
output : Two
Three
Five
Four

9. Write a Program to accept two numbers from user, perform addition and display result. Then ask user whether he want to perform more addition by pressing 1 or 0 to exit.

10. Write a Program to accept a number and print the number in reverse.
Input = 12345
output = 54321

11. Write a Program to accept a number form user and check whether the number is palindrome. If number is palindrome print it is palindrome else print not a palindrome.
Input = 121
output = It is palindrome
input  = 122
output = not a palindrome

12. Write a Program to accept a number from user until user enter 2000 as a input.

13. Write a Program to accept numbers from user until user enter 20 even numbers.

14. Write a Program to accept numbers from user until the sum of all entered number is less then 100.

### Methods Declaration and Calling
1. Write a Program to perform addition of two numbers by using a user defined function called add. Create a method called add which accept two arguments of type int and return an integer value by performing addition of these two arguments.
Hint : 
``` java
int add(int input1, int input2){
}
```
2. Write a Program to display hello world on output screen using a method called display, which doesn't accept any arguments and will not return any value. This method will print hello world on output screen.

3. Write a Program to create a method called isEven which accept one argument of type int and return a boolean value true if number is even and false if number is odd.

4. Write a Program to create a method called reverse, which accept one integer argument and return a integer which is reverse of the input.

5. Write a Program to create a method called isPalindrome, which accept one argument and return a boolean value true if number is palindrome else false. This function will use the reverse function for reversing the givn number.

