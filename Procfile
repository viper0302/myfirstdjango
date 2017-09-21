web: gunicorn config.wsgi:application
worker: celery worker --app=django_project.taskapp --loglevel=info
