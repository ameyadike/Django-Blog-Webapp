# Django Blog Webapp
This repository consist a basic webapp made with Django.
It will walk through all the steps involved in the project.



## Creating virtual environment in python and installing django.
----
Open command prompt and run the following code if you don't have virtualenv installed.
```bash
$pip install virtualenv
```

Move to the project directory/directory where you want to create a virtual environment. (My preferred terminal is GitBash.) and crate virtual environment using:
```bash
virtualenv <name_of_your_virtual_env>
```

To activate virtual environment using following command.
```bash
source <venv directory>/Scripts/activate
```
Once you are in virtual environment, you can install django
```bash
$pip install django
```

## Creating project and starting django app.
----
To start django project from django admin :
```bash
django-admin strartproject <name_of_project>
```
Once the project is created, change the directory to your project directory and start the django server as follows.
```bash
python manage.py runserver
```
The django dev server will be running on your local machine at port 8000.
To create a django app, run following command :
```bash
python manage.py startapp <appName>
```