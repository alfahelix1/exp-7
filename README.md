## 1. Aim

To implement various programs using looping statements in Python and to understand the working of iterative control structures such as for loop and while loop.


## 2. Functions Used

- print() – To display output
- input() – To take input from the user
- int() – To convert input into integer
- range() – To generate a sequence of numbers
- for loop – For definite iteration
- while loop – For indefinite iteration
- Arithmetic operators (+, -, *, /, %)
- Conditional statements (if)


## 3. Theory

Looping statements are used to execute a block of code repeatedly until a specified condition is satisfied. Python provides two main types of loops:

1. for loop – Used when the number of iterations is known.
2. while loop – Used when the number of iterations depends on a condition.

Loops help reduce code repetition and improve program efficiency. These programs demonstrate practical applications such as generating number series, factorial calculation, checking prime numbers, and pattern printing.


## 4. Algorithms (Problem-wise)

### Problem 1: Print Numbers from 1 to N

Algorithm:
1. Start
2. Input value of N
3. Use for loop from 1 to N
4. Print each number
5. Stop


### Problem 2: Print Even Numbers up to N

Algorithm:
1. Start
2. Input value of N
3. Use loop from 1 to N
4. If number % 2 equals 0, print number
5. Stop


### Problem 3: Print Odd Numbers up to N

Algorithm:
1. Start
2. Input value of N
3. Use loop from 1 to N
4. If number % 2 not equal to 0, print number
5. Stop


### Problem 4: Find Sum of First N Natural Numbers

Algorithm:
1. Start
2. Input N
3. Initialize sum = 0
4. Use loop from 1 to N
5. Add each number to sum
6. Print sum
7. Stop


### Problem 5: Find Factorial of a Number

Algorithm:
1. Start
2. Input number N
3. Initialize factorial = 1
4. Use loop from 1 to N
5. Multiply factorial by each number
6. Print factorial
7. Stop


### Problem 6: Check Whether a Number is Prime

Algorithm:
1. Start
2. Input number N
3. If N <= 1, print Not Prime
4. Else:
   - Check divisibility from 2 to N-1
   - If divisible, print Not Prime and stop
5. If no divisors found, print Prime
6. Stop


### Problem 7: Reverse a Number

Algorithm:
1. Start
2. Input number N
3. Initialize reverse = 0
4. While N > 0:
   - Extract last digit using N % 10
   - Add digit to reverse
   - Remove last digit using integer division
5. Print reversed number
6. Stop


### Problem 8: Check Whether a Number is Palindrome

Algorithm:
1. Start
2. Input number N
3. Store original number
4. Reverse the number using loop
5. Compare original and reversed numbers
6. If equal, print Palindrome
7. Else print Not Palindrome
8. Stop


### Problem 9: Print Multiplication Table of a Number

Algorithm:
1. Start
2. Input number N
3. Use loop from 1 to 10
4. Multiply N with loop variable
5. Print result
6. Stop


### Problem 10: Print Fibonacci Series up to N Terms

Algorithm:
1. Start
2. Input number of terms N
3. Initialize first = 0, second = 1
4. Print first and second
5. Use loop for remaining terms
   - next = first + second
   - Print next
   - Update first and second
6. Stop


### Problem 11: Pattern Printing (Star Pattern)

Algorithm:
1. Start
2. Input number of rows
3. Use outer loop for rows
4. Use inner loop to print stars
5. Print new line after each row
6. Stop


## 5. Conclusion

All the looping programs were successfully implemented using for and while loops in Python. The experiment improved understanding of iterative statements, logical problem solving, and structured programming. The objectives of the experiment were achieved successfully.
