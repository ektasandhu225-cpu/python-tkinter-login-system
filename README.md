# python-tkinter-login-system
Student Registration and Login System using Python Tkinter and MySQL
# 🎓 Student Registration and Login System

A simple **Student Registration and Login System** built using **Python, Tkinter GUI, and MySQL database**.  
This project allows students to register their details and log in securely using their email and password.

It demonstrates how **Python GUI applications interact with a MySQL database for authentication systems.**

---

## 📌 Features

✔ Student Registration Form  
✔ Login Authentication System  
✔ GUI Interface using Tkinter  
✔ MySQL Database Integration  
✔ Input Validation for Empty Fields  
✔ Success and Error Message Alerts  

---

##  Technologies Used

| Technology | Purpose |
| Python | Core programming language |
| Tkinter | GUI design |
| MySQL | Database storage |
| mysql-connector-python | Database connection |

---

## 📂 Project Structure
python-tkinter-login-system
│
├── Register(page).ipynb # Main Jupyter notebook code
├── README.md # Project documentation
├── LICENSE
└── .gitignore


---

## ⚙ Installation

Install required Python library:
pip install mysql-connector-python


---

## 🗄 Database Setup

1️⃣ Open **MySQL / phpMyAdmin**

2️⃣ Create Database
CREATE DATABASE student_db;


3️⃣ Create Table
CREATE TABLE ekta (
id INT AUTO_INCREMENT PRIMARY KEY,
name VARCHAR(100),
email VARCHAR(100),
phone VARCHAR(15),
password VARCHAR(100)
);



## ▶ How to Run the Project

1️⃣ Install Python  
2️⃣ Install required library:  
pip install mysql-connector-python

3️⃣ Start MySQL server  
4️⃣ Run the Jupyter Notebook
Register(page).ipynb

5️⃣ Use the GUI interface to register and login.

---

## 💡 How the System Works

### Registration
- User enters **Name, Email, Phone, Password**
- Data is stored in the MySQL database

### Login
- User enters **Email and Password**
- System verifies credentials
- If correct → Displays user name and phone
- If incorrect → Shows error message

---

## 🚀 Future Improvements

- Password Encryption
- Email Verification
- Better UI Design
- Student Dashboard
- Admin Panel

---

## 👩‍💻 Author

**Ekta Sandhu**







