# django_blog
git clone https://github.com/intoro/django_blog.git
cd django_blog/
virtualenv -p python3 venv
source venv/bin/activate
pip install django
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
