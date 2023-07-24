# Calculator

A simple HTML calculator that allows users to perform basic arithmetic calculations using buttons or keyboard input.

## How to Use

1. Clone the repository or download the HTML file to your local machine.
2. Open the `index.html` file in a web browser.

## Features

- The calculator supports the following arithmetic operations: addition (`+`), subtraction (`-`), multiplication (`*`), and division (`/`).
- Users can input numbers and perform calculations using the buttons provided.
- The calculator also responds to keyboard inputs for most of the buttons.
- To calculate the result, press the `=` button or the `Enter` key.

## Keyboard Shortcuts

- Numeric keys (`0-9`): Input the corresponding number.
- `+` key: Perform addition.
- `-` key: Perform subtraction.
- `*` key: Perform multiplication.
- `/` key: Perform division.
- `.` key: Input decimal point.
- `(` key: Open parentheses.
- `)` key: Close parentheses.
- `Backspace` key: Delete the last character from the calculation.
- `Enter` key: Calculate the result.

## Notes

- The calculator utilizes the `eval()` function to calculate the result of the expression stored in the `calculation` variable. While it may work for basic calculations, please be cautious as `eval()` can pose security risks and may lead to unexpected behavior with user inputs.
- The calculator does not handle division by zero, so dividing by zero will result in an error.
- For better readability and maintainability, consider moving the JavaScript code to a separate file and linking it using the `<script>` tag.
- The calculator's styling can be customized by modifying the CSS in the `<style>` tag.

Feel free to explore and experiment with the calculator! If using it for important or production purposes, consider implementing a more robust expression parser and evaluation mechanism to handle complex expressions and ensure the safety and accuracy of the calculations.
