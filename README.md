A demo Wagtail site, for seeing if django-simple-deploy can support Wagtail projects.

Usage
---

- Clone or download
```sh
$ uv venv .venv
$ source .venv/bin/activate
(.venv)$ uv pip install -r requirements.txt
(.venv)$ python manage.py migrate
(.venv)$ python manage.py check
(.venv)$ python manage.py createsuperuser
(.venv)$ python manage.py runserver
```

Click the admin link, and log in to make sure the project is working.
