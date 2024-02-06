## Creating the django project

- created a virtualenv env
- .\env\Scripts\Activate
- pip install django
- django-admin startproject mynotes
- cd mynotes
- python manage.py runserver

## Create api

- python manage.py startapp api
- add to settings.py
- work in the api folder (models, view, set up urls)
- migrate

## Admin

- create an admin super user
- register Note in api/admin.py

## Django Rest Framework

- pip install djangorestframework
- updated api view to work with rest framework
- created serializer
