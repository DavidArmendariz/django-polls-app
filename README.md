# Django Polls App

* Start a new project: `django-admin startproject <project_name>`
* Start a new app: `python manage.py startapp <app_name>`
* Run migrations: `python manage.py migrate`
* To make migrations from an app: `python manage.py makemigrations <app_name>`
* To see the SQL that the migration is going to make: `python manage.py sqlmigrate <app_name> <migration_version>`
* To check for any problems without making migrations or touching the database: `python manage.py check`
* To create a super user: `python manage.py createsuperuser`
