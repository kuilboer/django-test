# Notes

## Documentation links:
[django-admin documentation](https://docs.djangoproject.com/en/4.1/ref/django-admin/) - Documents `manage.py` functionality. 


## Models workflow

1. Create or change the app's model(s) 
2. Activate the app in the `PROJECT_DIRECTORY/settings.py` by adding it to the `INSTALLED_APPS = []` section.
3. Run `python manage.py makemigrations` to create the migrations for these changes;
4. Run `python manage.y migrate` to apply the model changes to the database.

other relevant commands:
1. `python manage.py check` to verify the code does not contain errors without making any migrations or touching the database;
2. `python manage.py sqlmigrate APPLICATION MIGRATION_#` this out puts the SQL of the changes that are comitted to the Database.

