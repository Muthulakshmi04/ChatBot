# Django Chatbot Image Gallery
##Introduction
A Django-based web application that integrates a chatbot to assist users in navigating and managing an image gallery.

#Installation
##Prerequisites
Python 3.x
Django
install dependency in requirements.txt

#Steps

python3 -m venv env
source env/bin/activate   # On Windows: env\Scripts\activate
Install dependencies:

pip install -r requirements.txt
Set up the database:

python manage.py migrate
Create a superuser:

python manage.py createsuperuser
Run the development server:

python manage.py runserver

Access the application at http://127.0.0.1:8000/ and interact with the chatbot to manage the image gallery. Admin interface available at http://127.0.0.1:8000/admin.
