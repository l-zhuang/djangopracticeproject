# Django Web App - A communication record stores Channel, Direction (inbound or outbound) and Summary

## Apply model change and run the server
- python3.11 manage.py makemigrations customer360
- python3.11 manage.py migrate
- python3.11 manage.py runserver


## Ensure Pip in installed and install Django
- python3.11 -m ensurepip
- python3.11 -m pip install Django
- django-admin startproject customer360

## To create virtual environment
- pip install --upgrade distro-info
- pip3 install --upgrade pip==23.2.1
- pip install virtualenv
- virtualenv djangoenv
- source djangoenv/bin/activate
