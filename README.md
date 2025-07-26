# Employee Management System

A robust Django-based CRUD application for managing employee records with a modern UI.

## 🚀 Features

- **Complete CRUD Operations**
  - Create new employee records
  - Read and display employee information
  - Update existing employee details
  - Delete employee records

- **Modern UI/UX**
  - Responsive Bootstrap 5 design
  - Enhanced form handling with Django Crispy Forms
  - Dynamic dropdown menus
  - Clean and intuitive interface

- **Robust Backend**
  - PostgreSQL database integration
  - Secure data handling
  - Efficient database queries
  - Form validation

## 🛠️ Technologies Used

- **Backend:** Django 5.2.4
- **Database:** PostgreSQL
- **Frontend:** Bootstrap 5
- **Form Handling:** Django Crispy Forms
- **Template Pack:** Crispy Bootstrap 5

## 📋 Prerequisites

- Python 3.13
- PostgreSQL
- pip (Python package manager)

## 🔧 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/gokul-s05/employee-management-system.git
   ```

2. Create and activate virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # For Unix/macOS
   venv\Scripts\activate     # For Windows
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Configure PostgreSQL:
   - Create database named 'EmployeeDB'
   - Update database settings in settings.py

5. Run migrations:
   ```bash
   python manage.py migrate
   ```

6. Start the development server:
   ```bash
   python manage.py runserver
   ```

## 🌟 Key Achievements

1. Implemented full-stack employee management system with seamless CRUD operations
2. Created responsive UI with modern design principles using Bootstrap 5
3. Developed production-ready architecture combining frontend, backend, and database management

## 🔐 Environment Variables

Create a `.env` file in the root directory and add:
```
DEBUG=True
SECRET_KEY=your_secret_key
DB_NAME=EmployeeDB
DB_USER=your_db_user
DB_PASSWORD=your_db_password
DB_HOST=localhost
```

## 📝 Project Structure

```
employee_project/
├── employee_project/      # Main project directory
│   ├── settings.py       # Project settings
│   └── urls.py          # Main URL configuration
├── employee_register/    # Main application
│   ├── models.py        # Database models
│   ├── forms.py         # Form definitions
│   ├── views.py         # View logic
│   └── templates/       # HTML templates
└── manage.py            # Django management script
```
