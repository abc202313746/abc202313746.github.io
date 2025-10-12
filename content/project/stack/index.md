---
title: Implementation of Stack Data Structure and Calculator
summary: A project to implement a stack data structure and utilize it to create a calculator that handles arithmetic expressions.
featured: featured.png
tags:
  - Data Structures
  - Algorithm
  - C++
  - Stack
  - Calculator
date: 2024-09-10
external_link: ''
---
For the Data Structures course, I implemented a **stack data structure** and used it to create a calculator that can handle arithmetic expressions. The project consisted of two main components:

## Stack Implementation
1. **Array-based Stack**: Implemented a stack using a dynamic array that can grow and shrink as needed.
2. **Basic Operations**: Implemented core stack operations:
   - `push()`: Add an element to the top
   - `pop()`: Remove and return the top element
   - `peek()`: View the top element without removing it
   - `isEmpty()`: Check if stack is empty
   - `isFull()`: Check if stack is full
3. **Error Handling**: Added comprehensive error checking for stack overflow and underflow conditions.

## Calculator Implementation
1. **Expression Parsing**: Developed a parser to handle arithmetic expressions in both infix and postfix notations.
2. **Conversion Algorithm**: Implemented the Shunting Yard algorithm to convert infix expressions to postfix notation.
3. **Expression Evaluation**: Created an evaluator that processes postfix expressions using the stack to calculate results.
4. **Support for Operations**:
   - Basic arithmetic (+, -, *, /)
   - Parentheses handling
   - Operator precedence
   - Multi-digit numbers

Through this project, I strengthened my understanding of:
- Stack data structure implementation and applications
- Algorithm design and optimization
- Expression parsing and evaluation techniques
- Error handling and edge cases in data structure implementations