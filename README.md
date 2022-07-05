# djangoforbeginners

- Chapter 1
	- install python 3
	- https://pypi.org/project/pipenv/
		- you no longer need to use pip and virtualenv separately
		- requirements.txt -> Pipfile / Pipfile.lock
    - `pip3 install pipenv`
	- install django
		- `pipenv install django~=3.1.0`
		- `pipenv shell`
	- Start a new project
		- `django-admin startproject config .`
	- Run the server
		- `python manage.py runserver`