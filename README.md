# Quiz Application (C Project)

## 📌 Project Description
This project is a console-based Quiz Application developed using the C programming language.  
The program provides a simple interactive quiz system where users can answer multiple-choice questions and receive their results instantly.

---

## 🖥 Program Flow
The program starts with a menu containing two options:

1. Start Quiz  
2. Exit  

When the user selects "Start Quiz", the quiz begins and multiple-choice questions are displayed one by one.  
After answering all questions, the program displays:

- Total Score (Correct answers out of 5)
- Percentage
- Pass/Fail Status

---

## 🛠 Implementation Details

### Arrays
Arrays are used to store:
- Questions
- Options
- Correct answers  

Both 2D and 3D arrays are used for data organization.

### Loops
A `for` loop is used to:
- Display each question
- Show corresponding options
- Accept user input
- Check the answer

A `do-while` loop is used for menu control.

### Conditional Statements
- `if` statements are used to check correctness.
- `switch` is used for menu selection.

### Percentage Calculation
Percentage is calculated using floating-point division.

---

## 📂 File Handling
All quiz results are stored in a file named:

`Quiz.txt`

The following data is saved:
- Score
- Percentage
- Pass/Fail Status

The file is opened in **append mode**, allowing multiple quiz attempts to be stored without overwriting previous results.

---

## 🎯 Concepts Used
- Functions
- Arrays (2D and 3D)
- Loops (for, do-while)
- Conditional Statements (if, switch)
- File Handling (fopen, fprintf, fclose)

---

## 🎓 Purpose of the Project
The main objective of this project is to improve:

- Structured programming skills in C
- Logical thinking
- Data organization using arrays
- Understanding of file handling

---

## 👤 Author
Nutan Surawase  
First-Year B.Tech Student
