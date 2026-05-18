# 💸 Expense Tracker Backend (SplitSmart API)

A Django REST Framework backend for a Splitwise-style expense sharing application.  
It manages users, groups, expenses, and shared balances.

---

## 🚀 Features

- User management (create / fetch users)
- Group creation and membership
- Expense tracking
- Paid-by and split calculation support
- REST API built using Django REST Framework
- SQLite database (default setup)

---

## 🛠️ Tech Stack

- Python 3.x
- Django
- Django REST Framework
- SQLite (default DB)

---

## 📁 Project Structure
expense_tracker/
│
├── expense_tracker/ # Main project settings
├── expenses/ # App (models, views, serializers)
├── db.sqlite3 # Database
├── manage.py
└── venv/ # Virtual environment (DO NOT PUSH)
