# Simple Calculator

This is a simple command-line calculator program written in Python. It allows users to perform basic arithmetic operations: addition, subtraction, multiplication, and division.

## Features

- Addition of two numbers
- Subtraction of two numbers
- Multiplication of two numbers
- Division of two numbers (with zero division handling)
- User-friendly menu interface

## How to Use

1. Run the program in a Python environment (Python 3.x recommended)
2. Select an operation by entering the corresponding number:
   - 1 for Addition
   - 2 for Subtraction
   - 3 for Multiplication
   - 4 for Division
3. Enter the two numbers when prompted
4. View the result of the operation

## Example Usage

```
Simple Calculator
Select operation:
1. Add
2. Subtract
3. Multiply
4. Divide

Enter choice (1/2/3/4): 1
Enter first number: 5
Enter second number: 3
Result: 8.0
```

## Error Handling

- The program handles division by zero and displays an appropriate error message
- Invalid menu selections are caught and reported

## Requirements

- Python 3.x

## Running the Program

Simply execute the Python script:

```bash
python calculator.py
```

## Functions

- `add(x, y)`: Returns the sum of x and y
- `subtract(x, y)`: Returns the difference between x and y
- `multiply(x, y)`: Returns the product of x and y
- `divide(x, y)`: Returns the quotient of x divided by y (with zero division check)
- `main()`: Handles user interaction and program flow

## License

This project is open source and available for anyone to use or modify.
