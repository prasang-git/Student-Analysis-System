# Student Analysis System

A Python-based Student Management and Academic Performance Analysis System that helps manage student records, calculate academic results, and visualize student performance using graphical charts.

---

## 1. Introduction

The Student Analysis System is a Python application developed to manage student information and analyse academic performance.

The system allows users to add student records, search for students, generate individual reports, calculate total and average marks, and visualize student performance through bar charts.

It uses CSV file handling to store student information and Matplotlib to generate graphical representations of academic results.

## 2. Problem Statement

Managing student records manually can be time-consuming and makes it difficult to search for individual student information, calculate academic performance, and maintain organized records.

The Student Analysis System provides a simple Python-based solution to store, retrieve, manage, and analyse student information efficiently.

## 3. Objectives

- Maintain student records digitally.
- Add new student information.
- Search students using roll numbers.
- Generate individual student performance reports.
- Calculate total and average marks.
- Display academic reports for all students.
- Visualize student performance using bar charts.
- Store and retrieve student information using CSV files.

## 4. Features

### 1. Add Student
Allows users to enter a student's roll number, name, and marks in Maths, Physics, and Python.

### 2. Search Student
Searches for a student using their roll number and displays their information.

### 3. Student Report
Generates an individual academic report containing student details, subject marks, total marks, and average marks.

### 4. Show All Students
Displays the records and average marks of all registered students.

### 5. Total Students
Displays the total number of students registered in the system.

### 6. Performance Chart
Generates a bar chart using Matplotlib to visually represent the average marks of students.

### 7. CSV File Storage
Stores student information in a CSV file, allowing records to be loaded and saved between program executions.

## 5. Technologies Used

| Technology | Purpose |
|---|---|
| Python | Main programming language |
| CSV | Reading and writing student records |
| Matplotlib | Creating performance charts |
| Lists | Storing student records and marks |
| Dictionaries | Organizing student information |

## 6. Python Concepts Used

- Variables and data types
- Lists and dictionaries
- User-defined functions
- For and while loops
- Conditional statements (if, elif, else)
- File handling
- CSV file operations
- Exception handling
- Type conversion
- Built-in functions such as sum() and len()
- Data visualization using Matplotlib

## 7. Project Structure

```text
Student-Analysis-System/
│
├── PythonProject.py
├── students.csv
├── README.md
├── requirements.txt
├── .gitignore
│
└── screenshots/
    ├── main-menu.png
    ├── add-student.png
    ├── search-student.png
    ├── student-report.png
    └── performance-chart.png
```

## 8. Dataset Description

The project uses a CSV file named `students.csv` to store student information.

The dataset contains five columns:

| Column | Description |
|---|---|
| roll | Student roll number |
| name | Student name |
| Maths | Mathematics marks |
| Physics | Physics marks |
| Python | Python subject marks |

The current dataset contains four student records.

### Sample Dataset

| Roll | Name | Maths | Physics | Python |
|---:|---|---:|---:|---:|
| 1 | student1 | 98 | 92 | 84 |
| 2 | student2 | 81 | 71 | 85 |
| 3 | student3 | 73 | 89 | 95 |
| 4 | student4 | 49 | 62 | 68 |

The program reads student records using Python's CSV module and converts marks into numerical values for calculations.

## 9. Installation and Setup

Follow these steps to run the project.

### Step 1: Clone the Repository

```bash
git clone https://github.com/prasang-git/Student-Analysis-System.git
```

### Step 2: Open the Project Directory

```bash
cd Student-Analysis-System
```

### Step 3: Install Dependencies

```bash
pip install -r requirements.txt
```

### Step 4: Run the Program

```bash
python PythonProject.py
```

Make sure Python 3.x is installed on your computer.

## 10. Requirements

- Python 3.x
- Matplotlib library
- CSV module (included in Python)

Install Matplotlib using:

```bash
pip install matplotlib
```

## 11. How the System Works

1. The program starts and loads student records from the CSV file.
2. The main menu is displayed.
3. The user selects an operation.
4. The selected function is executed.
5. Student information is retrieved, updated, or analysed as required.
6. Updated student records are saved to the CSV file when a new student is added.
7. The menu continues to appear until the user selects Exit.

## 12. Team Contributions

This project was developed collaboratively by a team of five members.

| Name | Contribution |
|---|---|
| Somil Goyal | Helped describe ideas and thoughts as real-life situations. |
| Ujjawal Malik | Helped in making the overall Python code. |
| Prabhu Dayal | Helped prepare the PDF and PPT and participated in the project presentation. |
| Prasang Patel | Helped in testing the program and writing code. |
| Jitesh Dhillon | Helped make the project efficient by helping everyone. |

## 13. Future Improvements

- Student record editing and deletion.
- Duplicate roll number prevention.
- Input validation for marks.
- Better error handling.
- Subject-wise performance analysis.
- Grade calculation.
- Exporting individual student reports.
- Graphical user interface (GUI).

## 14. Conclusion

The Student Analysis System demonstrates how Python programming can be used to solve a practical problem related to student record management and academic performance analysis.

The project combines functions, lists, dictionaries, loops, conditional statements, file handling, CSV operations, and data visualization in a single application.

Through this project, the team gained practical experience in Python programming, collaborative development, data management, and problem-solving.

---

## 15. Repository Information

**Project Name:** Student Analysis System

**Programming Language:** Python

**Team Size:** 5 Members

**Repository:** https://github.com/prasang-git/Student-Analysis-System