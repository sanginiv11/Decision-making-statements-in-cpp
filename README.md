# Decision-making-statements-in-cpp
Aim: Expt 6	To study and implement C++ decision making statements Loops.

Theory: 
(01) To check whether a number is odd or even. The program checks whether a number is even or odd. It uses the modulo operator '%' to divide the input number 'a' by 2. If the remainder is 0 ('a % 2 == 0'), the number is even; otherwise, it's odd. The program uses a simple 'if-else' condition and demonstrates basic input, arithmetic, and decision-making in C++.

(02) To find largest number from given 3 numbers. The program finds the largest among three numbers entered by the user. It uses nested 'if-else' conditions to compare the values:
- First, it compares 'num1' with 'num2'.
- If 'num1' is greater, it then checks whether 'num1' is also greater than 'num3'.
- If true, 'num1' is the largest; otherwise, 'num3' is.
- If 'num2' is greater than 'num1', the program compares 'num2' with 'num3' to find the larger between them.
  
(03) To determine whether  a given character is a vowel or consonant. The program checks if the entered character is a vowel by comparing it with all vowel letters (both uppercase and lowercase). If it matches, it prints "vowel"; otherwise, it prints "consonant". It uses 'if-else' and logical OR ('||') operators.

(04)Program for calculator using switch casee. The program is a simple calculator that performs basic arithmetic operations: addition, subtraction, multiplication, and division. It takes two numbers and an operator ('+', '-', '*', or '/') as input. Using a 'switch' statement, it performs the operation based on the chosen operator. It also checks for division by zero to avoid an error. The program demonstrates the use of 'switch-case' and basic arithmetic in C++.

(05)Switch-case-default to display a weekday. The program takes a number from 1 to 7 as input and uses a 'switch' statement to print the corresponding day of the week. Each 'case' represents a day (1 = Monday, 2 = Tuesday, etc.). If the input doesn't match any case from 1 to 7, the 'default' case prints "Invalid day number!". This program demonstrates the use of the 'switch-case' structure for menu-based or choice-driven output.

(06) My switch case program about the food menu.
This C++ program is designed to demonstrate a "nested 'switch-case' menu system", where the user selects from three main categories: "snacks", "meal", and "beverages". After choosing a category, the program is intended to display a corresponding submenu and allow the user to select a specific item. However, there is a logical flaw in the program: it only takes one input ('choice') and uses it for both the main menu and the submenu selections. As a result, the inner 'switch' statements do not function as intended, since they reuse the same value from the main menu instead of asking the user to choose a specific item within the category. The program provides a useful foundation for understanding how "nested 'switch-case' structures" can be used to create multi-level menu-driven applications in C++.

Conclusion: The previous six programs demonstrate the use of conditional and 'switch-case' statements in C++ for building menu-driven applications, making decisions, and performing operations like arithmetic, comparisons, and classifications. They highlight how control structures help in solving real-world problems through interactive user input and logical flow.
