Install python 3.8.8 from the link: https://www.python.org/ftp/python/3.8.8/python-3.8.8-amd64.exe

Commands (Execute one by one):
    pip install pipenv==2022.1.8
    pipenv shell
    pip install -r requirements.txt
    python manage.py makemigrations
    python manage.py migrate
    python manage.py createsuperuser (this will ask for username, email, password to create new admin user. Password will not show when you are typing on terminal / CMD)
    python manage.py runserver

Open the browser with "http://127.0.0.1:8000/documentation/" to refer the api documentation

Open the browser with "http://127.0.0.1:8000/admin/" to login to admin dashboard from there you can perform admin actions.
