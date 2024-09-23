# CodTech-task1
Overview: Tkinter-based Calculator Application
This project is a simple GUI-based calculator application developed using Python's Tkinter library. The calculator allows users to perform basic arithmetic operations like addition, subtraction, multiplication, and division. It features a clean and intuitive interface with buttons for numerical input, arithmetic operators, parentheses, and an evaluation function.

Key Components:
Graphical User Interface (GUI):

Tkinter Framework: The application uses Tkinter to create a windowed interface where users can interact with the calculator.
Text Display: The current calculation is displayed in a text field that updates dynamically as buttons are pressed.
Buttons: Numeric and operator buttons are laid out using Tkinter's grid system, mimicking a physical calculator's layout. Special buttons include:
Numbers (0-9)
Arithmetic operators (+, -, *, /)
Parentheses ((, ))
Clear (C) button to reset the input
Equals (=) button to evaluate the current expression
Functional Logic:

add_to_calculation(): This function is triggered when a button is pressed, adding the corresponding symbol to the ongoing calculation.
evaluate_calculation(): When the user clicks the = button, the current expression is evaluated using Python’s built-in eval() function. If the input is invalid, it catches the error and displays "error" on the screen.
clear_field(): Clears the current input and resets the calculation when the C button is pressed.
Error Handling:

Invalid expressions, such as division by zero or incorrectly formatted input, are handled gracefully. If an error occurs during evaluation, the text field shows "error," and the calculator is reset.
Design & Layout:

The layout is built using Tkinter's grid() method, making it adaptable and clean. Buttons are arranged logically in rows, similar to a traditional calculator.
The display is a large text field that shows both input and results.
Features:
Basic Arithmetic: Supports operations like addition, subtraction, multiplication, and division.
Parentheses: Allows grouping operations for more complex calculations.
Clear Function: The C button clears the current input.
Error Display: Displays "error" if an invalid expression is entered.
A window will open with the calculator interface, allowing for input and calculation.
