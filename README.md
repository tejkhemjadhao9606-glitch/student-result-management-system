# 🎓 Student Result Management System - Python

A beginner-friendly Python Student Result Management System that manages student details, calculates marks and percentages, and stores student results in an Excel file using Tkinter and OpenPyXL.

## 📌 Features

- Add new student records
- Store student details in an Excel file
- Enter marks for five subjects
- Automatically calculate total marks
- Automatically calculate percentage
- Generate Pass or Fail results
- Search student results using Roll Number
- Display individual student results
- View all student records in a table
- Display student details using Tkinter GUI
- Simple and user-friendly interface

## 💾 Data Storage

The project uses an Excel file named:

`student_results.xlsx`

The following information is stored:

- Student Name
- Roll Number
- Class
- Subject 1 Marks
- Subject 2 Marks
- Subject 3 Marks
- Subject 4 Marks
- Subject 5 Marks
- Total Marks
- Percentage
- Final Result (Pass/Fail)

**Result Calculation:**

- Total Marks = Sum of marks obtained in five subjects.
- Percentage = Total Marks / 5.
- Pass = All five subjects have at least 40 marks.
- Fail = If any subject has less than 40 marks.

## 🧠 Concepts Used

- Python Functions
- Tkinter GUI Development
- `if-else` Statements
- `for` Loops
- User Input Handling
- Variables and Data Types
- File Existence Checking
- Excel File Handling
- Reading and Writing Excel Data
- Searching Records
- Automatic Calculations
- `openpyxl` Library
- `ttk.Treeview` Widget
- Message Boxes
- Basic Condition Checking

## 📦 Libraries Used

Install `openpyxl` using:

```bash
pip install openpyxl
```

**Built-in Python Libraries:**

- `tkinter`
- `messagebox`
- `ttk`
- `os`

## ▶️ How to Run

**1.** Install Python on your computer.

**2.** Install the required library:

```bash
pip install openpyxl
```

**3.** Run the Python file:

```bash
python student_result_management.py
```

**4.** The application will automatically create the Excel file:

`student_results.xlsx`

**5.** Use the application to add students, search results, and view all student records.

## 👨‍💻 Developed By

**Tejas Jadhao**

GitHub: [@tejkhemjadhao9606-glitch](https://github.com/tejkhemjadhao9606-glitch)

---

⭐ If you find this project useful, don't forget to give it a star on GitHub!
