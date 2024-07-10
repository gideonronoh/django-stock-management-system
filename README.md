Create virtual environment  -  python -m venv myenv
Activate virtual environment - myenv\Scripts\activate
Install the packages - pip install -r requirements.txt
requirements.txt  -  asgiref==3.7.2
crispy-bootstrap4==2023.1
Django==4.2.9
django-crispy-forms==2.1
pillow==10.2.0
sqlparse==0.4.4
typing_extensions==4.9.0
tzdata==2023.4

python manage.py makemigrations
python manage.py migrate

python manage.py runserver
