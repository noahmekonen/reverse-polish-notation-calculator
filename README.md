# Reverse Polish Notation Calculator
A Java command-line calculator that evaluates mathematical expressions written in Reverse Polish Notation (RPN). 
The program uses a stack to process numbers and operators and can optionally display the evaluation process step by step.

# Features
- Evaluates Reverse Polish Notation expressions
- Supports addition (+)
- Supports subtraction (-)
- Supports multiplication (*)
- Supports division (/)
- Uses a stack to evaluate expressions
- Supports decimal numbers
- Optional step-by-step explanation of the evaluation
- Detects invalid or unsupported operators
- Detects missing operands
- Detects extra operands
- Allows the user to evaluate multiple expressions without restarting the program

# Example 
An RPN expression places the operator after its operands.
For example:
5 3 +
is equivalent to:
5 + 3
and produces:
END RESULT: 8.0
A more complex example: 
5 3 + 2 *
is equivalent to:
(5 + 3) * 2
and produces:
END RESULT: 16.0

# How it works
The calculator reads the expression one token at a time.
- If the token is a number, it is pushed onto the stack.
- If the token is an operator, the top two numbers are removed from the stack.
- The operation is performed on those numbers.
- The result is pushed back onto the stack.
- When the expression is complete, the remaining value is the final result.

# Concepts Used
- Java
- Stacks
- Scanners
- Loops
- Conditional statements
- Switch statements
- Methods
- Input validation
- Error handling
- Labeled loops
