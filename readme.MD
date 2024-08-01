# Django Clone Project

This is a simple clone project using the Django web framework. It demonstrates basic functionalities such as user authentication, CRUD operations, and template rendering.

## Features

- User Authentication (Login, Registration, Logout)
- CRUD operations for managing items
- Template rendering
- Basic admin interface

## Requirements

- Python 3.x
- Django 3.x

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/cyxjgmday/belajar-django.git
   cd django-clone

2. Create a virtual environment and activate it:

    ```bash
        python -m venv env
    source env/bin/activate  # On Windows use `env\Scripts\activate`

3. Install the required packages:

    ```bash
        pip install -r requirements.txt

4. Apply migrations:

    ```bash
        python manage.py migrate

5. Create a superuser:

    ```bash
    python manage.py createsuperuser

6. Run the development server:

    ```bash
    python manage.py runserver

7. Access the application at http://127.0.0.1:8000/.