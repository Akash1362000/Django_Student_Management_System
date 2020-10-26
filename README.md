# Django_Student_Management_System

DBMS Mini Project for DYPCOE

## Development
Note : Make sure you have Python version 3.8+

Environment Setup

`$ git clone https://github.com/Akash1362000/Django_Student_Management_System.git`

`$ cd Django_Student_Management_System/`

If virtualenv is not installed [(What is virtualenv?)](https://www.youtube.com/watch?v=N5vscPTWKOk&t=313s):

`$ pip install virtualenv`

Create a virtual environment

`$ virtualenv venv`

Activate the environment everytime you open the project

`$ source venv/Scripts/activate`

Install requirements

`$ pip install -r requirements.txt`

Run migrations for Database

`$ python manage.py makemigrations`

`$ python manage.py migrate`

Create superuser for Admin Login

`$ python manage.py createsuperuser`

Enter your desired username, email and password. Make sure you remember them as you'll need them in future.

eg.

    Username: admin
    
    Email: admin@admin.com
    
    Password: HighlyConfidentialPassword

All Set!

Now you can run the server to see your application up & running

`$ python manage.py runserver`

To exit the environment

`$ deactivate`


