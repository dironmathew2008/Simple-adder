Simple Python Adder

A small Python program that continuously adds numbers entered by the user and displays the running total.

Features

- Accepts numbers from the user
- Adds them to a running total
- Displays the current total after each input
- Runs continuously until the program is stopped

Code

total = 0

while True:
    num = int(input("Enter a number: "))
    total = total + num
    print("Current total:", total)

How to Run

1. Install Python
2. Run the program:

python adder.py

Example Output

Enter a number: 5
Current total: 5
Enter a number: 3
Current total: 8
Enter a number: 10
Current total: 18

Author

Dironmathew
