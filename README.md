# API USERS #

Requirements:
* Python3
* Virtualenv

Setup:
`
virtualenv env -p python3
source env/bin/activate
pip install requirements.txt
`

Updating database:
`python manage migrate` 

Creating migrations:
`python manage makemigrations` 

Running application:
`python manage runserver` 