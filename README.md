# 🚀 C Programming Portfolio

A comprehensive collection of C programs that demonstrate fundamental programming concepts, mathematical operations, and problem-solving skills.

## 📊 Overview

- **Total Programs:** 34
- **Categories:** 6
- **Lines of Code:** ~1,500+
- **Language:** C (C11 Standard)
- **Focus:** Programming Fundamentals

## 📂 Project Structure

### [01-Basic-Concepts](01-Basic-Concepts/) 📚
Programs that introduce fundamental C programming concepts
- `ascii-character-demo.c` - ASCII character values
- `printf_methods_comparison.c` - Different output methods using printf
- `programming-errors-explained.c` - Explanation of fatal vs. non-fatal errors

### [02-Mathematical-Programs](02-Mathematical-Programs/) 🧮
Calculators and mathematical operations
- `math-powers-table.c` - Table of squares and cubes (0-10)
- `basic_operations_calculator.c` - Sum, product, difference, quotient, and remainder
- `circle_calculator.c` - Circle diameter, circumference, and area
- `fahrenheit_to_celsius.c` - Temperature converter
- `discount_installment_calculator.c` - Discount and installment calculations
- `three_payment_calculator.c` - Division into 3 payments (down payment + 2 installments)
- `simple_average_calculator.c` - Simple arithmetic mean calculation

### [03-Number-Processing](03-Number-Processing/) 🔢
Numeric analysis, verification, and manipulation
- `digit-separator.c` - Digit separation of 5-digit numbers
- `multiple-checker.c` - Multiples verifier
- `even_odd_checker.c` - Even and odd number identifier
- `divisibility_by_three.c` - Divisibility by 3 checker
- `number_comparator.c` - Two-number comparator
- `five_number_comparator.c` - Five-number comparator (largest/smallest)
- `three_number_analyzer.c` - Three-number analysis (sum, average, product, largest/smallest)
- `triangular_number_verifier.c` - Triangular number verifier
- `triangular_number_analyzer.c` - Triangular number analysis
- `balanced_number_checker.c` - Balanced number verifier (7 digits)
- `two_digit_number_reverse.c` - Two-digit number reverser
- `three_digit_number_reverse.c` - Three-digit number reverser

### [04-Data-Manipulation](04-Data-Manipulation/) 🔄
Data and variable manipulation techniques
- `variable_swap_with_temp.c` - Variable swap using a temporary variable
- `swap_without_temporary.c` - Variable swap without a temporary variable
- `optimized_variable_swap.c` - Optimized variable swap
- `digit_interleaver.c` - Digit interleaver between two numbers

### [05-Patterns-Art](05-Patterns-Art/) 🎨
Visual pattern generation and ASCII art
- `checkerboard-pattern.c` - Chessboard pattern (8×8)
- `ascii_art_generator.c` - ASCII art generator (diamond pattern)
- `ascii_letter_art.c` - ASCII art of letters N and B
- `right_triangle_pattern.c` - Right triangle pattern with asterisks
- `numeric_square_generator.c` - Numeric square generator
- `digit_visualizer_ascii.c` - Digit visualizer using ASCII characters

### [06-Real-World-Applications](06-Real-World-Applications/) 💼
Practical applications simulating real-world scenarios
- `atm_cash_distributor.c` - ATM cash distributor
- `school_grade_calculator.c` - School grade calculator with final exam
- `simple_average_calculator.c` - Simple average calculator

## 🛠️ Compilation and Execution Instructions

### Prerequisites
- GCC (GNU Compiler Collection)
- Operating System: Windows, Linux, or macOS

### Compilation
```bash
# Compile a specific program
gcc program_name.c -o program_name

# Run the compiled program
./program_name

# Specific example
gcc 01-Basic-Concepts/ascii-character-demo.c -o ascii_demo
./ascii_demo
```

### Compilation with Recommended Flags
```bash
gcc -Wall -Wextra -pedantic -std=c11 program.c -o program
```

## 🎯 Demonstrated Skills

### Programming Fundamentals
- Control structures (if-else, loops)
- Input/output manipulation
- Function usage and modularization
- Error handling and validation

### Computational Mathematics
- Basic arithmetic operations
- Mathematical algorithms
- Geometric calculations
- Unit conversion

### Data Manipulation
- Variable operations
- Value swapping techniques
- Numeric processing
- Data transformation

### Algorithmic Thinking
- Problem solving
- Code optimization
- Logical structuring
- Case analysis

## 📈 Learning Progression

The programs are organized in increasing order of complexity:
1. **Basic Concepts** → Input/output, variables, operators
2. **Simple Mathematics** → Basic calculations and conversions
3. **Number Processing** → Algorithms and number analysis
4. **Data Manipulation** → Advanced variable techniques
5. **Patterns and Art** → Logical-visual thinking
6. **Practical Applications** → Integration of concepts

## 🌟 Highlights

- **Clean Code**: Clear naming and logical organization
- **Documentation**: Explanatory comments in Portuguese
- **Validation**: User input verification
- **Portability**: Code compatible with multiple systems
- **Educational**: Ideal for learning C programming

## 🤝 Contribution

This is an educational portfolio. For suggestions or improvements:
1. Fork the repository
2. Create a branch for your feature
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

---
### Developed as part of learning C programming, in the Computer Engineering course - UNASP-HT

---

© 2025 Nickolas Sponton Pires Bragato. All rights reserved.

---
**Note**: All programs were tested and compiled with GCC. Some programs use `setlocale(LC_ALL, "Portuguese")` for accent support.
