# Simple Python Calculator

A basic command-line calculator built with Python. This project serves as a foundational example demonstrating core programming concepts such as functions, user input, conditional statements, and error handling.

## Features

* **Addition (+)**: Adds two numbers.
* **Subtraction (-)**: Subtracts the second number from the first.
* **Multiplication (*)**: Multiplies two numbers.
* **Division (/)**: Divides the first number by the second, including robust error handling for division by zero.
* **User-Friendly Interface**: Guides the user through operation selection and numeric input.
* **Input Validation**: Employs `try-except` blocks to handle non-numeric input gracefully, prompting the user to re-enter valid data.
* **Continuous Calculation**: Allows users to perform multiple calculations in a single session without restarting the program.

## How to Run

To get this calculator running on your local machine, follow these simple steps:

1.  **Clone the repository (or download the `calcu.py` file):**
    ```bash
    git clone [https://github.com/YourUsername/your-repo-name.git](https://github.com/YourUsername/your-repo-name.git)
    cd your-repo-name
    ```
    (Replace `YourUsername` and `your-repo-name` with your actual GitHub username and repository name.)

2.  **Execute the Python script:**
    ```bash
    python calcu.py
    ```

## Code Overview

The calculator's logic is organized into clear, modular functions, enhancing readability and maintainability:

* `add(x, y)`: Returns the sum of `x` and `y`.
* `subtract(x, y)`: Returns the difference `x - y`.
* `multiply(x, y)`: Returns the product `x * y`.
* `divide(x, y)`: Returns the quotient `x / y`. This function explicitly checks if `y` is zero and returns an "Error! Division by zero." message to prevent runtime errors.

The primary `calculator()` function manages the user interaction loop, presents the menu, gathers input, performs validation, calls the appropriate arithmetic function, and displays the result. It also handles the "Do you want to perform another calculation?" prompt.

## Example Usage

Here's an example of how the calculator interacts with the user:
