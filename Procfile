web: gunicorn config.wsgi:application
worker: celery worker --app=well.taskapp --loglevel=info
