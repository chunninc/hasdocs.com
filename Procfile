web: newrelic-admin run-program gunicorn -k gevent --debug --log-level debug --spew hasdocs.wsgi -b 0.0.0.0:$PORT
celeryd: newrelic-admin run-python manage.py celeryd -E -B --loglevel=INFO
