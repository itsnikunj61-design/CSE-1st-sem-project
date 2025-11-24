SMART CALCULATOR
================

A comprehensive scientific calculator built with Python and Tkinter.

FEATURES

---

Basic Operations:

· Arithmetic: Addition (+), Subtraction (-), Multiplication (*), Division (/)
· Parentheses: ( ) for complex expressions
· Percentage: % calculations
· Decimal: Floating point numbers

Scientific Functions:

· Square Root: √
· Power Functions: x² (square), x³ (cube), xʸ (x to power y)
· Cube Root: ∛
· Factorial: x!

Trigonometric Functions (degrees):

· Basic: sinθ, cosθ, tanθ
· Inverse: asin, acos, atan
· Angle Conversion: deg (to degrees), rad (to radians)

Logarithmic & Constants:

· Natural Log: ln
· Base-10 Log: log
· Constants: π, 2π, e

Utility Buttons:

· C: Clear last character
· CE: Clear entire entry
· =: Evaluate expression

INSTALLATION

---

Requirements:

· Python 3.x
· Tkinter (usually included with Python)

To Run:
python calculator.py

USAGE

---

1. Click numbers and operators to build expressions
2. Click scientific functions after entering numbers
3. Use parentheses for complex calculations
4. Click buttons sequentially as you would type

Examples:

· 5 + 3 * 2 = 11
· sin(30) = 0.5
· 2² + 3³ = 31
· log(100) = 2

INTERFACE

---

· Color: Dodger blue background with white text
· Layout: 8 columns x 5 rows of buttons plus display
· Display: Shows current expression and results

BUTTON LAYOUT

---

Row 1: C, CE, √, +, π, cosθ, tanθ, sinθ
Row 2:1, 2, 3, -, 2π, acos, atan, asin
Row 3:4, 5, 6, *, ∛, xʸ, x³, x²
Row 4:7, 8, 9, /, ln, deg, rad, e
Row 5:0, ., %, =, log, (, ), x!

NOTES

---

· Trigonometric functions use degrees
· Inverse trig functions return degrees
· Use 'C' to backspace, 'CE' to clear all
· Follows standard mathematical order of operations
· Handles most common scientific calculations

TECHNICAL

---

· Built with Python Tkinter
· Uses math module for calculations
· Automatic degree/radian conversion
· Error handling for invalid input
