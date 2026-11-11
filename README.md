
# PDA and CFG Implementations Using Python

This repository contains three Python implementations demonstrating
how Context-Free Grammars (CFG) and Pushdown Automata (PDA) can
be used to recognize and validate different types of input strings.

## 1. Arithmetic Expression Validation

This program checks whether an arithmetic expression follows
the defined Context-Free Grammar.

It supports:
- Addition (+) and subtraction (-)
- Multiplication (*) and division (/)
- Identifiers and numeric values
- Parentheses and nested expressions

A CFG-based predictive stack parser is used to validate the
syntax of expressions while maintaining operator precedence.

## 2. Balanced Parentheses Checker

This program checks whether parentheses in a given string
are properly balanced and arranged.

It uses a stack-based Deterministic Pushdown Automaton (DPDA).

The program:
- Pushes an opening parenthesis onto the stack.
- Pops the stack when a matching closing parenthesis is found.
- Rejects unmatched or incorrectly ordered parentheses.
- Accepts the input if the stack is empty after processing.

## 3. Palindrome Checker

This program identifies whether a string is a palindrome
over the alphabet {a, b}.

It uses a Non-Deterministic Pushdown Automaton (NPDA)
simulation with stack-based processing.

The program:
- Stores the first half of the input on the stack.
- Nondeterministically guesses the midpoint.
- Matches the remaining characters with the stack.
- Accepts the string if all characters match and the stack
  becomes empty.

It supports both even-length and odd-length palindromes,
including the empty string.

## Technologies Used

- Python 3
- Google Colab
- Context-Free Grammars (CFG)
- Pushdown Automata (PDA)
- Stack-based parsing and validation

## Execution

1. Open the `.ipynb` notebook in Google Colab.
2. Run the code cells in sequential order.
3. View the accepted and rejected test inputs.
4. Examine the detailed stack execution traces.

## Implementation Results

All three implementations were tested using valid and invalid
input strings.

- Arithmetic Expression Validation: 8/8 tests passed.
- Balanced Parentheses Checker: 8/8 tests passed.
- Palindrome Checker: 10/10 tests passed.

**Overall: 26/26 tests passed.**

