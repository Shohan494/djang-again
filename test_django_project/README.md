## Django Again After 7 Years

- python install
- pip upgrade
- python venv ( virtual env )
```
In this step, you will create a virtual environment for you project. With the help of a virtual environment, you can create an isolated environment that won't affect other Python projects.

If you are not using a virtual environment, all your projects will be using the same Django version installed globally. It can lead your projects to fail when there is an update in Django with breaking changes.
```
 - make project folder
 - pip install django ( for installing in windows )
 - django-admin startproject test_project ( for django project creation )
 - python manage.py runserver ( run the **development** server )