# Calculator Project

This is a simple calculator program that allows users to perform basic arithmetic operations such as addition, subtraction, multiplication, and division. The program handles user input with error checking to ensure that only valid operations and numbers are used.

## Features

- Perform basic arithmetic operations: Addition, Subtraction, Multiplication, and Division
- Error handling for invalid inputs:
  - Invalid numbers
  - Invalid operators
  - Division by zero

## Functions

1. **subtraction(a, b)**: Returns the result of subtracting `b` from `a`.
2. **add(a, b)**: Returns the result of adding `a` and `b`.
3. **div(a, b)**: Returns the result of dividing `a` by `b`. Handles division by zero errors.
4. **mul(a, b)**: Returns the result of multiplying `a` and `b`.

## How to Run

1. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/yourusername/calculator-project.git
    ```

2. Navigate to the project directory:
    ```bash
    cd calculator-project
    ```

3. Run the program:
    ```bash
    python calculator.py
    ```

## Example Usage

```bash
Enter Operator (+, -, /, *): +
Enter value 1: 5
Enter value 2: 3
Result: 8.0
