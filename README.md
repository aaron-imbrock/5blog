# 5blog

A blog application that allows users to create, edit, and delete posts.
The homepage will list all blog posts and there will be a dedicated detail page for each individual
blog post. Limited CSS for styling.


## Setup
```
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt

# Assumes later creation of a custom user mode so don't run migrate
django-admin startproject django_project .
chmod +x manage.py
./manage.py startapp core

./manage.py runserver 
```
