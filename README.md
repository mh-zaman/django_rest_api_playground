# django_rest_api_playground


create a empty folder name "django_rest_api_playground"

open a terminal in the folder and run those commands one by one

python -m venv .env

.env\Scripts\activate

pip install django

python.exe -m pip install --upgrade pip

django-admin startproject django_rest_api_playground .

python manage.py migrate

python manage.py startapp basic_api

python manage.py runserver

close the terminal and open the whole folder in vscode and open django_rest_api_playground/settings.py

add these two apps in INSTALLED_APPS section

'basic_api',
'rest_framework',
'rest_framework_simplejwt.token_blacklist', # for logout token blacklist
pip freeze > requirements.txt
