# 🏦 Simple Banking Web Application
## 📌 Objective
-Develop a minimal web-based banking application using Flask.

-Simulate core banking functionalities:

-Account creation

-Balance checking

-Deposits and withdrawals

-Use SQLite for lightweight local data storage.

-Create an intuitive user interface with HTML forms embedded in Flask templates.

-Ensure easy deployment and portability using Docker.

-Provide a foundational project for learning CRUD operations and web development in Python
## 🛠️ Tech Stack
-Backend: Python (Flask)

-Database: SQLite

-Frontend: HTML (embedded in Flask with Jinja2)

-Containerization: Docker
## 🧩 Steps Included
1 Database Initialization

-On app start, bank.db is created with a table accounts (if not exists).

2 Web Routes

-/create – Create a new account.

-/balance – View current balance.

-/deposit – Add funds to an account.

-/withdraw – Withdraw funds from an account.

-/statement – Placeholder for future statement view.

3 Form-based Interaction

-Each route uses an HTML form with POST methods for inputs.

4 Run Instructions

-Flask app runs on http://0.0.0.0:5005.
## 💡 Key Insights
-Lightweight yet fully functional banking app using only Flask and SQLite.

-Demonstrates safe SQL operations using parameterized queries.

-Self-contained UI using a shared base template.

-Easy to deploy via Docker.
## 🚀 Getting Started
⚙️ Run Locally
## Option 1: Using Python directly
'''
pip install flask
python app.py
'''
Visit: http://localhost:5005
## Option 2: Using Docker
1 Build Docker Image
'''
-docker build -t banking-app .
'''
2 Run Container
'''
-docker run -p 5005:5005 banking-app
''' 
## 🧪 Features in Development
-Transaction history (Statement route placeholder)

-Account deletion and editing

-User authentication.
## 📁 File Structure
'''
-├── app.py         # Main Flask application
-├── Dockerfile     # Docker setup for containerization
-├── bank.db        # SQLite DB file (created at runtime)
'''


