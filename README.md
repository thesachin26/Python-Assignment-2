# Python-Assignment-2

# Module 3: Control Structures in Python

---

## 📜 Program Description

### **Task 1: Check if a Number is Even or Odd**
- Accepts a number from the user.
- Checks whether it is even or odd using an `if-else` statement.
- Prints the result.

### **Task 2: Calculate Sum from 1 to 50**
- Uses a `for` loop to iterate over numbers from **1 to 50**.
- Calculates the sum of all integers in this range.
- Displays the total sum.

---

## 💻 Code
```python
# Task 1: Even or Odd
number1 = input("Enter the Number: ")
number1 = int(number1)

if number1 % 2 == 0:
    print(number1, "is an even number")
else:
    print(number1, "is an odd number")

# Task 2: Sum from 1 to 50
total_sum = 0
for i in range(1, 51):
    total_sum = total_sum + i
print("The sum of numbers from 1 to 50 is :", total_sum)

