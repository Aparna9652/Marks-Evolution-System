# 📝 Marks Evaluation System - Python (Tkinter + MySQL)

This is a desktop-based **Marks Evaluation System** built using **Python's Tkinter GUI toolkit** and **MySQL** database. It allows users to **store** student marks and **retrieve** academic results based on Hall Ticket Numbers (HTNO).

---

## ✅ Features

- GUI to input student data and marks (Maths, Physics, Computer Science)
- Calculates:
  - Total Marks
  - Average Marks
  - Grade (Distinction, First Class, etc.)
- Saves data to MySQL database
- GUI to search and display student result by HTNO

---

## 🛠️ Technologies Used

- **Python 3.x**
- **Tkinter** – GUI interface
- **MySQL** – Database
- **mysql-connector-python** – Python-MySQL connector

---

## 🗃️ Database Setup

1. **Create MySQL database**:

```sql
CREATE DATABASE aditya;

**FILE STRUCTURE**
marks-evaluation-system/
├── insert_result.py       # Tkinter form to input and save data
├── view_result.py         # Tkinter form to view result
├── README.md
