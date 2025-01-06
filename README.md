
# Intelligent Financial Planning Hub

A **Django-based Expense Tracker** that allows users to securely manage their daily expenses. Users can register, log in, add expenses, and view transaction history. All transactions are securely stored in a MySQL database.

## Features

- **User Authentication:**
  - Registration and login with secure password management.
  - Session-based authentication.
- **Expense Management:**
  - Add, edit, and delete expenses.
  - View a detailed transaction history.
- **Responsive UI:**
  - Clean and intuitive user interface with a modern design.
  - Background image styled to full screen.
- **Database Integration:**
  - Data is stored in a MySQL database for reliability and scalability.
- **Secure Backend:**
  - Built with Django’s robust framework to handle data securely.

---

## Tech Stack

- **Frontend:**
  - HTML, CSS, Bootstrap
- **Backend:**
  - Django Framework
- **Database:**
  - MySQL
- **Languages:**
  - Python, JavaScript

---

## Getting Started

### Prerequisites

- Python 3.8 or above
- MySQL
- pip (Python package manager)

### Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/expense-tracker.git
   cd expense-tracker
   ```

2. **Set Up Virtual Environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Configure MySQL Database**
   - Create a MySQL database:
     ```sql
     CREATE DATABASE expense_tracker;
     ```
   - Update `DATABASES` in `settings.py`:
     ```python
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
     ```

5. **Run Migrations**
   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```

6. **Start the Server**
   ```bash
   python manage.py runserver
   ```

7. **Access the Application**
   - Open your browser and visit: `http://127.0.0.1:8000`

---


## Screenshots
![Screenshot 2024-12-30 195313](https://github.com/user-attachments/assets/18860495-02ba-42d3-aa12-541a4370a778)





