to install Django on your virtual environment:

```
python3 -m venv django-env
source django-env/bin/activate #for linux users
pip install django
```

to create a project with Django execute this command:

```
django-admin startproject mysite
```


now you will see some files and folders created by django you can use to build your application.

to test that everything is alright, lets run our application to see if its working or not.
to run a django application with dev server run this command:

```
cd ./mysite
python ./manage.py runserver 
```


now if you visit  http://127.0.0.1:8000/ you will see the home page of Django.

![[Pasted image 20240118113200.png]]
to change the port and network interface your application will run:

```
python manage.py runserver 8080
python manage.py runserver 0.0.0.0:8000
```

