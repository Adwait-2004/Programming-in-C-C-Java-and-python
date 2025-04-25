# project-1
# Programming-in-C-C-Java-and-python
# Multi-Language Calculator Project

A simple calculator implementation in multiple programming languages (C++, Python, and Java). This project demonstrates basic programming concepts including input handling, conditional statements, and mathematical operations.

## Features

- **Basic Arithmetic Operations**: Addition, subtraction, multiplication, and division
- **Advanced Operations**: Power, modulus, and square root
- **Error Handling**: Proper handling for division by zero and invalid operations
- **User Input**: Interactive console input for numbers and operation selection

## Implementations

### C++ Implementation

The C++ version uses the `<iostream>` and `<cmath>` libraries to implement the calculator functionality.

#### How to compile and run:
```bash
g++ calculator.cpp -o calculator
./calculator
```

### Python Implementation

The Python version uses the built-in `math` module for advanced operations.

#### How to run:
```bash
python calculator.py
```

### Java Implementation

The Java version uses the `Scanner` class for input and `Math` class for advanced operations.

#### How to compile and run:
```bash
javac Calculator.java
java Calculator
```

## Usage

1. Run the program in your preferred language
2. Enter the first number when prompted
3. Enter the second number when prompted
4. Choose an operation:
   - `+` for addition
   - `-` for subtraction
   - `*` for multiplication
   - `/` for division
   - `^` for power
   - `%` for modulus
   - `r` for square root (uses only the first number)

## Example

```
Enter first number: 16
Enter second number: 4
Choose operation (+, -, *, /, ^, %, r for square root): r
Result: Square root of 16 = 4
```

## Project Structure

```
calculator-project/
├── cpp/
│   └── calculator.cpp
├── python/
│   └── calculator.py
├── java/
│   └── Calculator.java
└── README.md
```

## Future Improvements

- Add a loop to allow multiple calculations
- Implement more advanced operations (trigonometric functions, logarithms)
- Add a graphical user interface
- Improve input validation
- Add unit tests
