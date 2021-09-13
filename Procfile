release: python manage.py migrate
web: gunicorn Cinemania.wsgi
python manage.py collectstatic --noinput