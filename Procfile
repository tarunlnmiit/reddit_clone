web: gunicorn config.wsgi:application
worker: newrelic-admin run-program celery worker --app=reddit.taskapp --loglevel=info
