# steps to run the project

## activate ur environemnt:
* conda activate 

## now install dependencies
* pip install -r requirements.txt

## now database migration
* python manage.py makemigrations
* python manage.py migrate

## now run:
python manage.py runserver