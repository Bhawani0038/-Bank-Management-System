# -Bank-Management-System
A full-stack Bank Management System built with Python (Flask) and MySQL. Supports customer operations like deposits, withdrawals, and fund transfers, plus an admin dashboard with insights on total customers, categorized accounts, and total bank balance. Clean UI and secure, scalable backend.


# 🏦 Bank Management System

A full-stack web-based **Bank Management System** built using **Python (Flask)** and **MySQL**. It supports core banking functionalities for customers and provides an insightful admin dashboard for monitoring the bank's financial health.

---

## 🚀 Features

### 👤 Customer Portal
- Account creation with validation
- Login/logout system
- Deposit and withdrawal operations
- Fund transfers between accounts
- Balance check
- Mini statement (transaction history)
- Password update

### 🧑‍💼 Admin Dashboard
- View total number of customers
- Categorize customers based on balance
- Monitor total bank balance
- Dashboard analytics (charts/tables)
- Search/view customer details
- Export customer data

---

## 💻 Tech Stack

| Layer        | Technology         |
|--------------|--------------------|
| Frontend     | HTML, CSS, JavaScript |
| Backend      | Python (Flask)     |
| Database     | MySQL              |
| Others       | Jinja2 Templating, Bootstrap (optional) |

---

## 📁 Project Structure

bank-management-system/
│
├── static/
│ ├── css/
│ ├── js/
│ └── images/
│
├── templates/
│ ├── login.html
│ ├── dashboard.html
│ ├── customer_home.html
│ └── admin_dashboard.html
│
├── models/
│ ├── customer.py
│ └── transaction.py
│
├── app.py
├── db_config.py
├── requirements.txt
├── sample_data.sql
├── .gitignore
└── README.md



---

## ⚙️ Getting Started

### 🔧 Prerequisites
- Python 3.x
- MySQL Server
- Git

### 📥 Installation

git clone https://github.com/yourusername/bank-management-system.git
cd bank-management-system
python -m venv venv
source venv/bin/activate        # On Windows: venv\Scripts\activate
pip install -r requirements.txt


🛠️ Setup MySQL Database
Create a database: bank_system

Run the SQL script in sample_data.sql to set up schema and test data.

🔐 Run the Application

python app.py


Sample Admin Login

Username: admin@bank.com
Password: admin123


🧪 Testing Scenarios
Invalid login attempts

Withdrawals exceeding balance

Transfers between invalid accounts

Password mismatch on update

Account creation with invalid data

![image](https://github.com/user-attachments/assets/a7cad738-a996-4f98-87c5-2cdd721d8018)
![image](https://github.com/user-attachments/assets/a7cad738-a996-4f98-87c5-2cdd721d8018)

![image](https://github.com/user-attachments/assets/0cf55a81-17fd-47aa-8667-64df37b0e19a)
![image](https://github.com/user-attachments/assets/0cf55a81-17fd-47aa-8667-64df37b0e19a)



🔐 Security Measures
Password hashing (bcrypt recommended)

SQL Injection prevention via parameterized queries

Session-based authentication and user control

✨ Future Enhancements
Email/SMS notifications

Loan and EMI modules

Dashboard charts with Chart.js or Plotly

API layer for mobile support

🙌 Acknowledgements
Developed by Bhawani Singh
Data Analytics Trainer | Python & Web Developer
