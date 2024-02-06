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
- set up more in the view and url

## Create new folder for frontend

- ran into CORS error when trying to work on multiple ports on local host.
- python -m pip install django-cors-headers
- add corsheaders to settings.py installed apps and middleware
