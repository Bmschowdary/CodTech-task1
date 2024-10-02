Calculator using Tkinker

This is a Python-based graphical user interface (GUI) calculator created with the **Tkinter** library. The calculator supports basic arithmetic operations such as addition, subtraction, multiplication, and division. It features a user-friendly interface with buttons for digits, operations, and special characters like parentheses, and displays results in a text field.

Features

- Perform basic arithmetic operations: addition (`+`), subtraction (`-`), multiplication (`*`), and division (`/`).
- Supports parentheses for complex expressions.
- Easy-to-use layout with clear and equals buttons for calculation control.
- Real-time updating of the expression as the user enters digits and operators.

Requirements

- Python 3.x
- Tkinter (included with standard Python distribution)

How to Run

1. Clone or download the repository to your local machine:
   
https://github.com/Bmschowdary/CodTech-task1.git
   

2. Navigate to the project directory:
   
   "cd tkinter-calculator"
  

3. Run the Python script:
   
   "python calculator.py"
   

The calculator window will appear, allowing you to enter expressions and see the results in real time.
Code Overview

Global Variable

- calculation: A string that stores the current mathematical expression entered by the user. It updates as the user presses buttons.

### Functions

1. add_to_calculation(symbol):
   - Appends the pressed button's value (number or operator) to the `calculation` string.
   - Updates the `text_result` widget with the current expression.
   
   Parameters:
   - `symbol`: A digit, operator, or special character to be added to the current expression.

2. evaluate_calculation():
   - Evaluates the mathematical expression stored in `calculation` using Python’s `eval()` function.
   - If the expression is valid, it updates the display with the result.
   - If the expression is invalid, it shows an error message.

3. clear_field():
   - Resets the `calculation` string and clears the display.

User Interface (UI) Setup

- The main window is created using Tkinter’s `tk.Tk()` function.
- A `Text` widget named `text_result` is used to display the current expression and result.
- Buttons for digits, operations, and control (clear, equals) are created using `tk.Button()`, and arranged in a grid layout for ease of use.

Layout

- The calculator uses a grid-based layout. Number buttons (`0-9`) are arranged in rows 2 through 5, while operators and special characters are placed in column 4 and other specific positions.
- The equals (`=`) and clear (`C`) buttons span two columns to make them easier to press.

Event Loop

The event loop (`root.mainloop()`) keeps the application running, allowing user interaction with the calculator interface.

Button Layout

| Row | Column 1 | Column 2 | Column 3 | Column 4 |
|-----|----------|----------|----------|----------|
| 2   | 1        | 2        | 3        | `+`      |
| 3   | 4        | 5        | 6        | `-`      |
| 4   | 7        | 8        | 9        | `/`      |
| 5   | `(`      | 0        | `)`      | `*`      |
| 6   | `C` (spans 2 columns) | `=` (spans 2 columns) |

Future Improvements

- Add support for additional mathematical functions (e.g., square root, exponentiation).
- Implement keyboard input for quicker calculations.
- Add memory functionality (M+, M-, MR).



---

Enjoy using the calculator! Feel free to contribute to the project by submitting pull requests or reporting issues.
![ts-1](https://github.com/user-attachments/assets/898debad-6cda-40f7-bb61-4bb270564e49)
