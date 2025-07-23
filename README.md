# Decision-making-statements-in-cpp
Aim: Expt 6	To study and implement C++ decision making statements Loops.
Algorithm:
(01)
1. Start the program.
2. Declare an integer variable.
3. Prompt the user to enter a number and read the input.
4. Check if the number is divisible by 2 (using modulus operator %).
5. If the remainder is 0, print "The number is even."
6. Else, print "The number is odd."
7. End the program.

(02)
1. Start the program.
2. Declare three integer variables.
3. Prompt the user to enter the first number and read the input.
4. Prompt the user to enter the second number and read the input.
5. Prompt the user to enter the third number and read the input.
6. If the first number is greater than the second:
   a. If the first number is also greater than the third, print that the first number is the largest.
   b. Else, print that the third number is the largest.
7. Else (the second number is greater than or equal to the first):
   a. If the second number is greater than the third, print that the second number is the largest.
   b. Else, print that the third number is the largest.
8. End the program.

(03)
1. Start the program.
2. Declare a character variable.
3. Prompt the user to enter a letter and read the input.
4. Check if the character is a vowel (a, e, i, o, u, A, E, I, O, U).
5. If it is a vowel, print "The character is a vowel."
6. Else, print "The character is a consonant."
7. End the program.

(04)
1. Start the program.
2. Declare two variables for numbers and one for the result.
3. Declare a variable for the operator.
4. Prompt the user to enter the first number and read the input.
5. Prompt the user to enter an operator (+, -, *, /) and read the input.
6. Prompt the user to enter the second number and read the input.
7. Use a switch-case statement to check the operator:
8. If '+', add the numbers and print the result.
9. If '-', subtract the numbers and print the result.
10. If '*', multiply the numbers and print the result.
11. If '/', check if the second number is not zero:
12. If not zero, divide and print the result.
13. If zero, print an error message for division by zero.
14. For any other operator, print "Invalid operator!"
15. End the program.

(05)
1. Start the program.
2. Declare an integer variable for the day number.
3. Prompt the user to enter a day number (1-7) and read the input.
4. Use a switch-case statement to check the day number:
 - If 1, print "Monday".
 - If 2, print "Tuesday".
 - If 3, print "Wednesday".
 - If 4, print "Thursday".
 - If 5, print "Friday".
 - If 6, print "Saturday".
 - If 7, print "Sunday".
5. For any other number, print "Invalid day number!"
6. End the program.

(06)
1. Start the program.
2. Display the main menu: 1. snacks, 2. meal, 3. beverages.
3. Prompt the user to enter their main choice and read the input.
4. Use a switch-case statement for the main choice:
 - If choice is 1 (snacks):
     a. Display snacks menu: 1. samosa, 2. vadapav, 3. maggi.
     b. Prompt the user to enter their snacks choice and read the input.
     c. Use a switch-case for snacks choice and print the selected item.
 - If choice is 2 (meal):
     a. Display meal menu: 1. veg, 2. non-veg.
     b. Prompt the user to enter their meal choice and read the input.
     c. Use a switch-case for meal choice and print the selected item.
 - If choice is 3 (beverages):
     a. Display beverages menu: 1. tea, 2. coffee, 3. cold drink.
     b. Prompt the user to enter their beverages choice and read the input.
     c. Use a switch-case for beverages choice and print the selected item.
5. End the program.
Theory: 
(01)
- To check whether a number is odd or even.
- The program checks whether a number is even or odd.
- It uses the modulo operator '%' to divide the input number 'a' by 2.
- If the remainder is 0 ('a % 2 == 0'), the number is even; otherwise, it's odd.
- The program uses a simple 'if-else' condition and demonstrates basic input, arithmetic, and decision-making in C++.

(02) 
- To find largest number from given 3 numbers.
- The program finds the largest among three numbers entered by the user. It uses nested 'if-else' conditions to compare the values:
- First, it compares 'num1' with 'num2'.
- If 'num1' is greater, it then checks whether 'num1' is also greater than 'num3'.
- If true, 'num1' is the largest; otherwise, 'num3' is.
- If 'num2' is greater than 'num1', the program compares 'num2' with 'num3' to find the larger between them.
  
(03) 
- To determine whether a given character is a vowel or consonant.
- The program checks if the entered character is a vowel by comparing it with all vowel letters (both uppercase and lowercase).
- If it matches, it prints "vowel"; otherwise, it prints "consonant".
- It uses 'if-else' and logical OR ('||') operators.

(04)
- Program for calculator using switch casee.
- The program is a simple calculator that performs basic arithmetic operations: addition, subtraction, multiplication, and division.
- It takes two numbers and an operator ('+', '-', '*', or '/') as input. Using a 'switch' statement, it performs the operation based on the chosen operator.
- It also checks for division by zero to avoid an error.
- The program demonstrates the use of 'switch-case' and basic arithmetic in C++.

(05)
- Switch-case-default to display a weekday.
- The program takes a number from 1 to 7 as input and uses a 'switch' statement to print the corresponding day of the week.
- Each 'case' represents a day (1 = Monday, 2 = Tuesday, etc.).
- If the input doesn't match any case from 1 to 7, the 'default' case prints "Invalid day number!".
- This program demonstrates the use of the 'switch-case' structure for menu-based or choice-driven output.

(06) 
- My switch case program about the food menu.
- This C++ program is designed to demonstrate a "nested 'switch-case' menu system", where the user selects from three main categories: "snacks", "meal", and "beverages".
- After choosing a category, the program is intended to display a corresponding submenu and allow the user to select a specific item.
- However, there is a logical flaw in the program: it only takes one input ('choice') and uses it for both the main menu and the submenu selections.
- As a result, the inner 'switch' statements do not function as intended, since they reuse the same value from the main menu instead of asking the user to choose a specific item within the category.
- The program provides a useful foundation for understanding how "nested 'switch-case' structures" can be used to create multi-level menu-driven applications in C++.

Conclusion: The previous six programs demonstrate the use of conditional and 'switch-case' statements in C++ for building menu-driven applications, making decisions, and performing operations like arithmetic, comparisons, and classifications. They highlight how control structures help in solving real-world problems through interactive user input and logical flow.

