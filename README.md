# Python_Basic

## Beginner Topics

- ✅ Syntax & Basics – Variables, Data Types, Operators
- ✅ Control Flow – If-else, Loops (for, while)
- ✅ Functions – Defining & Calling Functions, Arguments, Return Values
- ✅ Data Structures – Lists, Tuples, Sets, Dictionaries
- ✅ String Manipulation – Formatting, Methods, Slicing

## Intermediate Topics

- ✅ File Handling – Read/Write Files (txt, csv, json)
- ✅ Error Handling – Try, Except, Finally
- ✅ List Comprehensions – Efficient list operations
- ✅ Modules & Libraries – Importing, Using Built-in & External Libraries
- ✅ Working with Databases – SQL Queries with Python (SQLite, Pandas)

## Advanced Topics (Useful for Data Analysis)

- ✅ Pandas & NumPy – Dataframes, Series, Arrays, Data Processing
- ✅ Matplotlib & Seaborn – Data Visualization
- ✅ Regular Expressions (re module) – Pattern Matching
- ✅ Automation – OS Module, Scheduling Tasks

#

# Python Learning Roadmap

## 🟢 Beginner Topics
### ✅ Syntax & Basics – Variables, Data Types, Operators
Python has a simple syntax that makes it easy to learn.
```python
# Variables and Data Types
x = 10  # Integer
y = 3.14  # Float
name = "Alice"  # String
is_active = True  # Boolean

# Operators
sum_value = x + y  # Addition
is_greater = x > 5  # Comparison
```

---
### ✅ Control Flow – If-Else, Loops (for, while)
Control structures manage how your code executes.
```python
# If-Else
age = 18
if age >= 18:
    print("Eligible to vote.")
else:
    print("Not eligible.")

# For Loop
for i in range(5):
    print(i)

# While Loop
count = 0
while count < 5:
    print(count)
    count += 1
```

---
### ✅ Functions – Defining & Calling Functions, Arguments, Return Values
```python
def greet(name):
    return f"Hello, {name}!"

print(greet("Alice"))
```

---
### ✅ Data Structures – Lists, Tuples, Sets, Dictionaries
```python
# List
fruits = ["apple", "banana", "cherry"]

# Tuple (Immutable)
coordinates = (10, 20)

# Set (Unique Values)
numbers = {1, 2, 3, 3}

# Dictionary (Key-Value Pairs)
student = {"name": "Alice", "age": 25}
```

---
### ✅ String Manipulation – Formatting, Methods, Slicing
```python
text = "Hello, World!"
print(text.lower())  # Convert to lowercase
print(text[0:5])  # Slice first 5 characters
```

---
## 🔵 Intermediate Topics
### ✅ File Handling – Read/Write Files (txt, csv, json)
```python
# Writing to a file
with open("file.txt", "w") as f:
    f.write("Hello, Python!")

# Reading a file
with open("file.txt", "r") as f:
    content = f.read()
    print(content)
```

---
### ✅ Error Handling – Try, Except, Finally
```python
try:
    num = int(input("Enter a number: "))
    print(10 / num)
except ZeroDivisionError:
    print("Cannot divide by zero!")
except ValueError:
    print("Invalid input! Enter a number.")
finally:
    print("Execution completed.")
```

---
### ✅ List Comprehensions – Efficient List Operations
```python
squares = [x**2 for x in range(10)]
print(squares)
```

---
### ✅ Modules & Libraries – Importing, Using Built-in & External Libraries
```python
import math
print(math.sqrt(25))
```

---
### ✅ Working with Databases – SQL Queries with Python (SQLite, Pandas)
```python
import sqlite3

conn = sqlite3.connect("database.db")
cursor = conn.cursor()
cursor.execute("CREATE TABLE IF NOT EXISTS users (id INTEGER PRIMARY KEY, name TEXT)")
conn.commit()
conn.close()
```

---
## 🔴 Advanced Topics (Useful for Data Analysis)
### ✅ Pandas & NumPy – Dataframes, Series, Arrays, Data Processing
```python
import pandas as pd
import numpy as np

data = np.array([[1, 2, 3], [4, 5, 6]])
df = pd.DataFrame(data, columns=["A", "B", "C"])
print(df)
```

---
### ✅ Matplotlib & Seaborn – Data Visualization
```python
import matplotlib.pyplot as plt
import seaborn as sns

data = [10, 20, 30, 40]
plt.plot(data)
plt.show()
```

---
### ✅ Regular Expressions (re module) – Pattern Matching
```python
import re
text = "Email: test@example.com"
pattern = r"[a-zA-Z0-9_.+-]+@[a-zA-Z0-9-]+\.[a-zA-Z0-9-.]+"
match = re.search(pattern, text)
print(match.group())
```

---
### ✅ Automation – OS Module, Scheduling Tasks
```python
import os
print(os.getcwd())  # Get current directory
```

