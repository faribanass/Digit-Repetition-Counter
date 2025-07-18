# Digit-Repetition-Counter

This program defines a function to count how many times a specific digit appears in a given number.

## Function Explanation

- `repeat(number, digit)`:  
  Takes two integers as input — a number and a digit — and returns how many times the digit appears in the number.  
  It repeatedly extracts the last digit of the number by using modulus (`% 10`) and compares it to the target digit. If they match, it increments a counter. Then, it removes the last digit by integer division (`// 10`) and continues until all digits have been checked.

## How to Use

- The program asks the user to input a number and then a digit.
- It prints how many times the digit repeats in the number.
