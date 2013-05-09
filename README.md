{{project_name}}
=====================

This project was started with the Django installable plugin template. This has created a development environment that does not require an entire django deployment to develop and test an installable module. The following instructions will be useful for anyone developing this project.

Using the development environment
---------------------------------
Install requirements

    pip install fabric
    pip install -r requirements.txt

Setup db

    fab syncdb
    fab migrate

Start server

    fab serve

Using the Python shell

    fab shell

Running tests

    fab test

Creating South schema migrations

    fab schema
    fab migrate



#REPLACE EVERYTHING AFTER THIS WITH YOUR INFO#

Django installable plugin template
Copyright 2013 Jeremy Satterfield
Licensed under GPLv3 see COPYING for license
