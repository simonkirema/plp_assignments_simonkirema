# 🧮 Basic Calculator Program

A simple command-line calculator built in Python that allows a user to input two numbers and perform a selected arithmetic operation.

## 📌 Features

- Accepts user input for two numbers
- Supports basic arithmetic operations: addition (`+`), subtraction (`-`), multiplication (`*`), and division (`/`)
- Outputs the result in a clear format
- Handles division by zero gracefully

## 💻 How It Works

1. User inputs two numbers
2. User selects an operation (`+`, `-`, `*`, or `/`)
3. Program performs the operation and displays the result
4. If division by zero is attempted, the program shows an error message

## 📄 Example Output

```bash
Please enter the first number: 12  
Please enter the second number: 4  
Please enter an operation (+, -, *, /): *  
12.0 * 4.0 = 48.0
num1 = float(input("Please enter the first number: "))
num2 = float(input("Please enter the second number: "))
operation = input("Please enter an operation (+, -, *, /): ")

🧠 Code Snippet
python
Copy
Edit
num1 = float(input("Please enter the first number: "))
num2 = float(input("Please enter the second number: "))
operation = input("Please enter an operation (+, -, *, /): ")

if operation == '+':
    result = num1 + num2
    print(f"{num1} + {num2} = {result}")
elif operation == '-':
    result = num1 - num2
    print(f"{num1} - {num2} = {result}")
elif operation == '*':
    result = num1 * num2
    print(f"{num1} * {num2} = {result}")
elif operation == '/':
    if num2 != 0:
        result = num1 / num2
        print(f"{num1} / {num2} = {result}")
    else:
        print("Division by zero error")
else:
    print("Invalid operation")
🚀 Getting Started
Make sure you have Python 3 installed.

Save the above code into a file called calculator.py.

Run the script:

bash
Copy
Edit
python calculator.py
📂 Project Structure
bash
Copy
Edit
calculator/
├── calculator.py     # Main Python script
└── README.md         # This documentation file
✅ Requirements
Python 3.x

📬 Contributing
If you'd like to contribute to this project, feel free to fork the repository and open a pull request.

© 2025 Simon kirema – All rights reserved.
