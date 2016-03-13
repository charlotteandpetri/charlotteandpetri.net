web: gunicorn config.wsgi:application
worker: celery worker --app=cnp_blog.taskapp --loglevel=info
