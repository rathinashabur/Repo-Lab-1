release: sh -c 'python3 manage.py migrate && python3 manage.py loaddata initial_catalog_data.json'
web: gunicorn Repo-Lab-1.wsgi --log-file -