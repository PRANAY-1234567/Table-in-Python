📘 Multiplication Table Program in Python


📌 Overview

This Python program generates the multiplication table of a given number entered by the user.
It uses a for loop to iterate through numbers from 1 to 10 and prints the multiplication results.

This program is a basic example for learning loops, user input, and formatted output in Python.

⚙️ Source Code
num = int(input("Enter a number: "))

for i in range(1, 11):
    print(num, "x", i, "=", num * i)
🧠 How It Works
1️⃣ Take Input From User
num = int(input("Enter a number: "))

input() reads the number entered by the user.

int() converts the input from string to integer.

2️⃣ Loop From 1 to 10
for i in range(1, 11):

range(1, 11) generates numbers from 1 to 10.

Each iteration represents one line of the multiplication table.

3️⃣ Print the Multiplication Result
print(num, "x", i, "=", num * i)

This prints the multiplication in a readable format.

Example structure:

number x multiplier = result
▶️ Example Execution
Input
Enter a number: 5
Output
5 x 1 = 5
5 x 2 = 10
5 x 3 = 15
5 x 4 = 20
5 x 5 = 25
5 x 6 = 30
5 x 7 = 35
5 x 8 = 40
5 x 9 = 45
5 x 10 = 50
🔑 Key Concepts Demonstrated

User input handling

Type conversion (int)

for loops

range() function

Basic arithmetic operations

⏱️ Time Complexity

O(1)

The loop runs a fixed 10 iterations, so the execution time remains constant.

🚀 Possible Improvements
1️⃣ Using Formatted Strings
print(f"{num} x {i} = {num * i}")
2️⃣ Custom Table Range
limit = int(input("Enter table limit: "))
for i in range(1, limit + 1):
    print(f"{num} x {i} = {num * i}")
📚 Learning Outcomes

After studying this program, you will understand:

How to take user input in Python

How to use loops for repeated calculations

How to display results in a structured format

Basic logic for mathematical programs

<img width="584" height="945" alt="image" src="https://github.com/user-attachments/assets/668a73a6-8ebf-47b5-a03f-2e4c3a3a4e14" />

