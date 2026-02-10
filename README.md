SQLite Database Application (Python)
📌 Project Title

Database Application using SQLite and Python

🧾 Description

This project demonstrates how to build a simple database-driven application using Python and SQLite.
It covers all essential CRUD operations (Create, Read, Update, Delete) with best practices such as parameterized queries to prevent SQL injection and proper database connection handling.

🎯 Objectives

Connect Python with SQLite database

Create database tables programmatically

Perform CRUD operations

Use secure parameterized queries

Manage database commits and connections correctly

🛠️ Technologies Used

Programming Language: Python 3

Database: SQLite

Library: sqlite3 (built-in Python module)

📂 Project Structure
database_app/
│
├── database_app.py
├── users.db        (auto-created)
└── README.md

⚙️ Features Implemented

✔ Connect to SQLite database
✔ Create tables dynamically
✔ Insert user records
✔ Fetch records using SELECT queries
✔ Update existing records
✔ Delete records
✔ Prevent SQL injection using parameterized queries
✔ Commit and close database connections safely

▶️ How to Run the Project
Step 1: Clone or Download

Download the project files or copy database_app.py into a folder.

Step 2: Run the Script
python database_app.py

Step 3: Output

A users.db file will be created automatically

User records will be inserted, fetched, updated, and deleted

Output will be displayed in the terminal

🧪 Sample Output
Users in database:
(1, 'Manoj', 'manoj@gmail.com', 22)
(2, 'Anita', 'anita@gmail.com', 25)

After update & delete:
(1, 'Manoj', 'manoj@gmail.com', 23)

🔐 Security Best Practices Used

Parameterized SQL queries (?)

Avoids direct user input in SQL strings

Proper connection closing to prevent memory leaks

🚀 Future Enhancements

Menu-driven CLI application

Exception handling and logging

User input validation

GUI using Tkinter

Migration to MySQL or PostgreSQL

👨‍💻 Author

Manoj KS
Python Intern

📜 
