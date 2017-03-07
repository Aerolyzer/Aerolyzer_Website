# Aerolyzer\_App

The code behind the [Aerolyzer](https://github.com/Aerolyzer/Aerolyzer) mobile web application

## Dependencies
[Django](https://www.djangoproject.com/)
* To install the Django dependency:
``` conda install django``` or ```pip install django```

## Running the Aerolyzer app
To run the Aerolyzer app locally (as a Django project):

* ```cd Aerolyzer/```
* ```python manage.py runserver```

* Open your browser to http://127.0.0.1:8000/app/

##Important things to note are:

1.Postgresql 9.5.g (min requirement) should be installed and running on port 5432. Postgresql can be downloaded at https://www.postgresql.org/download/
2.The database in Postgresql should be set up with the settings as outlined in settings.py namely:
NAME, USER and PASSWORD settings.
