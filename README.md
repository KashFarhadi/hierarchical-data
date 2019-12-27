# Welcome to Django! Hierarchical Data. Using a Modified Preorder Tree Traversal (MPTT), we can treat all our data like a gigantic tree. In this project, I've created a simple Django server that uses MPTT models from django-mptt to create a Dropbox-esque web interface where you can create "folders" and "files" in an arbitrary structure and then display that structure.

### Completed by
Kash Farhadi

## Running the Application

Fork, Clone, Navigate to directory
Create and start a a virtual environment

for pipenv:
`pipenv install`

`pipenv shell`

`python manage.py makemigrations {foldername}` 
(where foldername is the top level folder for this project)

`python manage.py migrate`

Create an admin account (superuser) if you would like to test admin features and access the admin page. Easily create users and objects from the built in django visual interface

`python manage.py createsuperuser`

Finally start the django server using: 
`python manage.py runserver`

Access the homepage at 
`http://127.0.0.1:8000/` 
`http://localhost:8000/`

Admin page
`http://127.0.0.1:8000/admin` 
`http://localhost:8000/admin`


##### Built using Python 3.8 and the latest version of Django (2.1.2 as of this writing)