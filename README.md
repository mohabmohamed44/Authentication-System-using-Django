# Django Authentication System

## Project Description

This is a robust authentication system built using Python and Django. It provides a secure and customizable solution for user registration, login, and account management. reset password and change password by sending email to the user using SendGrid.


![Django Auth System](images/ScreenShot.png)

## Features

- User registration with email verification
- Secure login and logout functionality
- Password reset via email

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/django-auth-system.git
   ```

2. Navigate to the project directory:
   ```bash
   cd django-auth-system
   ```

3. Create a virtual environment:
   ```bash
   python -m venv venv
   ```

4. Activate the virtual environment:
   - On Windows using PowerShell:
     ```powershell
     .\venv\Scripts\Activate.ps1
     ```
   - On Windows using Command Prompt:
     ```cmd
     venv\Scripts\activate
     ```
   - On macOS and Linux:
     ```bash
     source venv/bin/activate
     ```

5. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

6. Apply migrations:
   ```bash
   python manage.py migrate
   ```

7. Create a superuser:
   ```bash
   python manage.py createsuperuser
   ```

8. Run the development server:
   ```bash
   python manage.py runserver
   ```

9. Open your browser and visit `http://localhost:8000`