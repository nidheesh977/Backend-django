Install python 3.8.8

Commands (Execute one by one):
    cd Backend-django
    pip install pipenv==2022.1.8
    pipenv shell
    pip install -r requirements.txt
    python manage.py makemigrations
    python manage.py migrate
    python manage.py createsuperuser (this will ask for username, email, password to create new admin user)
    python manage.py runserver

Open the browser with "http://127.0.0.1:8000/documentation/" to refer the api documentation

Open the browser with "http://127.0.0.1:8000/admin/" to login to admin dashboard from there you can perform admin actions.