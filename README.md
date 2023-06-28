# Django web-app

Django web-app with postgres Backend.

You should have an existing postgres-Database to use this app.

## Installation

```console
git clone https://github.com/dxas90/django-postgresql-gunicorn.git
cd django-postgresql-gunicorn
pip install virtualenv
virtualenv venv
source venv/bin/activate
pip install -r requirements.txt
python manage.py makemigrations
python manage.py migrate
gunicorn xproject.wsgi:application -c gunicorn.conf.py
```
