# Django Task Manager with Authentication

A simple Django project that allows users to register, log in, and manage their own tasks. Each user can create, view, update, and delete tasks securely, with all data isolated per user.

The project is intended for learning and practicing core Django concepts, including authentication, models, views, templates, and basic CRUD operations.

---

## Features

- User registration and login
- Create, view, update, and delete tasks
- Tasks are user-specific
- Clean and beginner-friendly project structure

---

## Setup Instructions

```bash
# 1. Clone the repository
git clone https://github.com/Pramish747/Django-Task-Manager-with-Authentication.git
cd Django-Task-Manager-with-Authentication

# 2. Create and activate a virtual environment
python -m venv venv
venv\Scripts\activate

# 3. Install dependencies
pip install django

# 4. Apply database migrations
python manage.py makemigrations
python manage.py migrate

# 5. Run the development server
python manage.py runserver

# 6. Open the application in your browser
# http://127.0.0.1:8000/
