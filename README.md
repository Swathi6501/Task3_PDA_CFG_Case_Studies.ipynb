
# CLA-2: Case Study-Based Analysis and Design Using PDA and CFG

## Student Details

- **Name:** Swathi Palanisamy
- **Register Number:** RA2411026050013
- **Department:** CSE AIML
- **Section:** A
- **Subject:** Formal Language and Automata
- **Subject Code:** 21CSC301T
- **Assignment:** CLA-2

---

## Project Overview

This project presents three case studies based on
Context-Free Grammars (CFG) and Pushdown Automata (PDA).

The case studies demonstrate how stack-based automata
recognize and validate different context-free languages.

## Case Studies

### 1. Arithmetic Expression Validation

- Validates arithmetic expressions using a CFG.
- Supports addition, subtraction, multiplication and division.
- Handles identifiers, numbers and nested parentheses.
- Uses a CFG-based predictive PDA simulation.
- Test cases: 8
- Passed: 8
- Failed: 0

### 2. Balanced Parentheses Checker

- Checks whether parentheses are properly balanced.
- Uses the grammar: S -> (S)S | ε
- Uses a deterministic stack-based PDA.
- Demonstrates push and pop operations.
- Test cases: 8
- Passed: 8
- Failed: 0

### 3. Palindrome Checker

- Checks palindrome strings over the alphabet {a, b}.
- Uses the grammar: S -> aSa | bSb | a | b | ε
- Uses a non-deterministic PDA simulation.
- Demonstrates midpoint guessing and stack matching.
- Test cases: 10
- Passed: 10
- Failed: 0

---

## Technologies Used

- Python 3
- Google Colab
- Context-Free Grammars (CFG)
- Pushdown Automata (PDA)
- Deterministic PDA (DPDA)
- Non-Deterministic PDA (NPDA)
- GitHub

## Project Structure

CLA2_Task3_PDA_CFG/
|
|-- CLA2_Task3_PDA_CFG_Case_Studies.ipynb
|-- Case_Study_Report.pdf
|-- README.md

## Execution Instructions

1. Open the Google Colab notebook.
2. Run the code cells in sequential order.
3. Observe the test case validation results.
4. Examine the PDA execution traces.
5. Refer to the case study report for theoretical explanations.

## Overall Results

| Case Study | Total Tests | Passed | Failed |
|------------|-------------|--------|--------|
| Arithmetic Expression Validation | 8 | 8 | 0 |
| Balanced Parentheses Checker | 8 | 8 | 0 |
| Palindrome Checker | 10 | 10 | 0 |
| **Total** | **26** | **26** | **0** |

## Learning Outcomes

- Understanding Context-Free Grammars.
- Designing Pushdown Automata.
- Understanding stack-based language recognition.
- Differentiating deterministic and non-deterministic PDA.
- Analyzing context-free languages and their limitations
  under finite automata.

---

**Academic Project:** CLA-2  
**Subject:** Formal Language and Automata (21CSC301T)
