xhtml2pdf
Django==3.0.5
django-widget-tweaks==1.4.8
sqlparse==0.3.1

****

**Instructions**
- Install the Requirements: pip install -r requirements.txt
- Then, make database migrations: python manage.py makemigrations
- python manage.py migrate
- And finally, run the application: python manage.py runserver

For Admin Account, please create one with superuser!

Instructions for Execution

1. Open the folder and open the command promt from folder (right click and hit 'open terminal'), then execute one by one the below command: 
python -m venv venv

.\venv\Scripts\activate

pip install django

pip install -r requirement.txt

python manage.py makemigrations

python manage.py migrate

python manage.py runserver

At this stage you will get a url like http://127.0.0.1:8000, click on the url, the website will open in a browser

Then it is need to create superuser to login. now use below command and use username and password and email as your wish 

python manage.py createsuperuser
python manage.py runserver


if encounter any error like sequrity issue, then copy the entire project file to another folder and try again. 


if issue like value error, then close your whole browser, then open the incognito or private mode, then try again. 
