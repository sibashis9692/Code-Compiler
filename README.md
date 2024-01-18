# 1. Project's Title

DSA_Problem_Solver

# 2. Project Description

DSA Problem Solving is a web-based application built with Django for efficiently tackling and mastering Data Structures and Algorithms through interactive coding challenges

# 3. How to Install and Run the Project

## Requirements

Make sure you have the following dependencies installed before running the application:

- Python3 =< latest version

## Installation
1. Create a virtual environment:
```
python -m venv venv
```
2. Activate the virtual environment:
```
venv\Scripts\activate
```
3. Clone the Repository:
```
git clone https://github.com/sibashis9692/DSA-Problem-Solver.git
cd DSA-Problem-Solver
```
4. install dependencies:
```
pip install -r requirements.txt
```
## Database Setup
Before running the application, set up the database as follows:

1. Create a MySQL database for the project.
2. Update the database settings in settings.py:

```
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.mysql',
        'NAME': 'your_database_name',
        'USER': 'your_database_user',
        'PASSWORD': 'your_database_password',
        'HOST': 'localhost',
        'PORT': '3306',
    }
}
```
3. Run migrate and migrations:
```
python manage.py makemigrations
python manage.py migrate
```
## Running the Application
```
python manage.py runserver
```
The server should now be running at http://localhost:8000
