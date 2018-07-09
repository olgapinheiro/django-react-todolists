web: gunicorn todotoday.wsgi --limit-request-line 8188 --log-file -
worker: celery worker --app=todotoday --loglevel=info
