# 🐍 Python Fundamentals Project – Data Technician Bootcamp

This project was completed as part of a **Data Technician Bootcamp**, where I developed core Python programming skills through hands-on exercises and problem-solving tasks.

The project focuses on building logic, performing calculations, and interacting with users using fundamental Python concepts.

---

## 🚀 Key Skills Demonstrated

### 🧠 Core Programming Concepts
- Using **variables** to store and manipulate data  
- Applying **type casting** to convert between data types  
- Writing clear output using the `print()` function  
- Capturing user input with the `input()` function  

---

### 🔀 Control Flow & Logic
- Using **if / elif / else statements** to control program flow  
- Building logical conditions to make decisions  
- Solving problems step-by-step using structured logic  

---

### 🔁 Loops & Iteration
- Using **for loops** to iterate over ranges and datasets  
- Using **while loops** for repeated execution based on conditions  
- Automating repetitive tasks efficiently  

---

[Link to Colab workbook Day 1 - Task 1](https://colab.research.google.com/drive/1bnp-KFWR1o-Iw7-No0d7LPPBhnNi5kTf?usp=sharing)

[Link to Colab workbook Day 2 - Task 1](https://colab.research.google.com/drive/1eUoDbry4tB_KW5lklBIvh_3og93e8qWZ?usp=sharing)

---

## 💡 Project Example – FizzBuzz

A classic programming challenge used to demonstrate logic and control flow:

```python
# Loop through numbers from 1 to 100
for i in range(1, 101):
    if i % 3 == 0 and i % 5 == 0:
        print("fizzbuzz")
    elif i % 3 == 0:
        print("fizz")
    elif i % 5 == 0:
        print("buzz")
    else:
        print(i)
