# C++ Experiment 3: Conditional Statements & Decision Making

---

## 🎯 Aim

- Use conditional (`if`, `else if`, `else`) statements in C++ to:
  - Determine **grade based on average marks**
  - Identify the **quadrant of a point** in 2D space
  - Check whether a **number is positive, negative, or zero**

---

## 🧠 Objectives

- Understand and implement conditional logic using C++ `if-else` constructs  
- Apply decision-making to real-world problems  
- Develop programs to analyze numeric data and provide descriptive output  
- Gain confidence in nested and multi-branch conditional statements

---

## 🛠 Tools Used

- **Programming Language**: C++  
- **Compiler**: g++ (GNU Compiler Collection)  
- **Editor/IDE**: Visual Studio Code  
- **Operating System**: Windows 10  

---

## 📘 Algorithm Explanation

### ➤ Grade Calculator

1. Start the program  
2. Declare variables for 5 subjects: `math`, `english`, `chemistry`, `physics`, `history`  
3. Take user input for all subject marks  
4. Calculate total marks: `total = math + english + chemistry + physics + history`  
5. Compute average: `average = total / 5.0`  
6. Use conditional statements to assign grades:
   - `O` if 80 ≤ average ≤ 90  
   - `A+` if 70 ≤ average < 80  
   - `A` if 60 ≤ average < 70  
   - `B` if 50 ≤ average < 60  
   - `C` if 40 ≤ average < 50  
   - `F` if average < 40  
7. Display total, average, and grade  
8. End the program  

---

### ➤ Quadrant Identifier

1. Start the program  
2. Prompt the user to input x and y coordinates  
3. Use nested conditionals to determine:
   - **First Quadrant**: x > 0 and y > 0  
   - **Second Quadrant**: x < 0 and y > 0  
   - **Third Quadrant**: x < 0 and y < 0  
   - **Fourth Quadrant**: x > 0 and y < 0  
   - **Origin**: x == 0 and y == 0  
   - **Y-axis**: x == 0 and y ≠ 0  
   - **X-axis**: y == 0 and x ≠ 0  
4. Display the result  
5. End the program  

---

### ➤ Number Sign Checker

1. Start the program  
2. Prompt the user to enter a number  
3. Use conditionals to check:
   - If number > 0 → Positive  
   - If number < 0 → Negative  
   - If number == 0 → Zero  
4. Display the result  
5. End the program  

---

## ✅ Conclusion

This experiment introduced the usage of **conditional statements**
