# mobile cuts django application code
setup virutalenv for development

git clone https://github.com/moble-cuts/mobilecuts.git

cd mobilecuts

virtualenv venv -p python3

. env/bin/activate

pip install Django

pip install -r requirements/development.txt # this is not required as of yet until configured properly

python manage.py migrate

python manage.py runserver

Read django documentation for more info https://docs.djangoproject.com/en/2.2/



