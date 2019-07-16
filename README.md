# mobilecuts
# mobile cuts django application code
# setup virutalenv for development

git clone repo
cd mobilecuts
virtualenv venv -p python3
source env/bin/activate
pip install -r requirements/development.txt # this is not required as of yet until configured properly
python manage.py migrate
python manage.py runserver

# Read django documentation for more info https://docs.djangoproject.com/en/2.2/



