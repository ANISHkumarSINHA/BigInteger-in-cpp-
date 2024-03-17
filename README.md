💥Introduction
In C/C++, the maximum number of digits a long long int can have is 20. However, there are scenarios where we need to work with numbers larger than this, such as when dealing with 
cryptographic algorithms or large-scale mathematical computations. To address this, we introduce a new data type called BigInt, which allows us to handle arbitrarily large integers.
This project implements various operations on BigInt, including addition, subtraction, multiplication, division, modulo, exponentiation, square root, comparison, and conversion.

💥Approach
The BigInt data type is implemented using C++ strings, allowing us to store numbers as sequences of characters. For efficiency, the digits are stored in reverse order. 
Basic mathematical concepts are employed for performing operations such as addition, subtraction, and multiplication. The project also includes functions for calculating
Fibonacci numbers, factorials, and Catalan numbers using BigInt.

💥Operations Implemented
Defining BigIntegers: Initialize BigInt numbers.
Number of Digits: Determine the number of digits in a BigInt.
Increment/Decrement: Implement post/pre-increment and post/pre-decrement operations.
Addition: Add two BigInt numbers.
Subtraction: Subtract one BigInt number from another.
Multiplication: Multiply two BigInt numbers.
Division: Divide one BigInt number by another.
Modulo: Find the modulo of two BigInt numbers.
Square Root: Compute the floor integer square root of a BigInt.
Exponentiation: Raise a BigInt number to a power.
Conversion: Convert a simple integer to a BigInt.
Fibonacci: Calculate Fibonacci numbers up to a specified limit.
Factorial: Calculate factorial of a BigInt.
Catalan: Calculate Catalan numbers up to a specified limit.
Comparison: Compare two BigInt numbers to determine their relative magnitude.

💥Applications of BigInt
The BigInt data type finds applications in various domains, including:

Calculating large Fibonacci numbers.
Computing Catalan numbers.
Finding factorials of large numbers.
Handling cryptographic algorithms.
Performing large-scale mathematical computations.
