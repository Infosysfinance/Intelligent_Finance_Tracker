# Intelligent_Finance_Tracker
This is the Team Project of Infosys Springboard Team 2


A Django-based Expense Tracker that allows users to securely manage their daily expenses. Users can register, log in, add expenses, and view transaction history. All transactions are securely stored in a MySQL database.

**Features**
**User Authentication:**
Registration and login with secure password management.
Session-based authentication.
**Expense Management:**
Add and delete expenses.
View a detailed transaction history.
**Responsive UI:**
Clean and intuitive user interface with a modern design.
Background image styled to full screen.
**Database Integration:**
Data is stored in a MySQL database for reliability and scalability.
**Secure Backend:**
Built with Django’s robust framework to handle data securely.
**Tech Stack******
Frontend:
HTML, CSS, Bootstrap
Backend:
Django Framework
Database:
MySQL
Languages:
Python, JavaScript
Getting Started
Prerequisites
Python 3.8 or above
MySQL
pip (Python package manager)
Installation
Clone the Repository

bash
Copy code
git clone https://github.com/Infosysfinance/Intelligent_Finance_Tracker
cd expense-tracker
Set Up Virtual Environment

bash
Copy code
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install Dependencies

bash
Copy code
pip install -r requirements.txt
Configure MySQL Database

Create a MySQL database:
sql
Copy code
CREATE DATABASE expense_tracker;
Update DATABASES in settings.py:
python
Copy code
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.mysql',
        'NAME': 'expense_tracker',
        'USER': 'your_mysql_user',
        'PASSWORD': 'your_mysql_password',
        'HOST': 'localhost',
        'PORT': '3306',
    }
}
Run Migrations

bash
Copy code
python manage.py makemigrations
python manage.py migrate
Start the Server

bash
Copy code
python manage.py runserver
Access the Application

Open your browser and visit: http://127.0.0.1:8000

