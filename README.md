🧮 Simple CLI Calculator – Python
📖 Description
This is a command-line calculator built in Python that performs basic arithmetic operations:
➕ Addition
➖ Subtraction
✖️ Multiplication
➗ Division
% Modulus
^ Exponentiation

It allows users to:

Perform multiple operations in one session

View calculation history

Exit or continue based on user input

🧰 Features
Simple input prompts for number and operation

Handles division by zero errors gracefully

Stores and displays history of all calculations

Loop-based interaction until the user chooses to exit

🚀 How to Use
Run the script:

bash
Copy
Edit
python calculator.py
Follow the prompts:

Enter the first number

Choose an operation: +, -, *, /, %, ^

Enter the second number

View the result

Optionally view calculation history

Choose to continue or exit

📌 Sample Interaction
pgsql
Copy
Edit
enter the first number : 5
 * ,+ ,- ,/ ,% , ^ : +
 enter the second number :  3
5.0 + 3.0
result is  8.0
do you want to see the history, yes/no: yes
['5.0 + 3.0 = 8.0']
do you want to continue?, yes/no: no
Thank you for using our calculator
⚠️ Error Handling
Division by zero is caught with a user-friendly message:

pgsql
Copy
Edit
error: cannot perform division by zero
🛠️ Functions Included
Function	Description
addition(a, b)	Returns a + b
subtraction(a, b)	Returns a - b
multiplication(a, b)	Returns a * b
division(a, b)	Returns a / b (or error if b == 0)
modulus(a, b)	Returns a % b
power(a, b)	Returns a ** b

🧼 Notes
Inputs are always cast to float to support decimals.

Results are printed in real-time.

The code uses a simple loop and if-else logic — no external libraries are required.
