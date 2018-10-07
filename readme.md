Here is an app built with django framework using mysql database

To get started;

Download anaconda from www.anaconda.com

clone this project 

Install and run as Anaconda prompt in Administrative mode in windows  

Run the following commands;

- conda install -c anaconda mysql-connector-python 

- conda create --name myvenv python=3

- conda activate myvenv 

- pip install -r requirements.txt

- cd to project folder with manage.py file and run python manage.py migrate to populate table data to your database details as specified in settings.py on your using phpmyadmin on xampp or wamp.

- Run python manage.py runserver


Make sure you have your xampp or wamp running and have created a database with name 'myscrumy' or any custom name that corresponds with the DATABASES field in the settings.py file to migrate the database table with python manage.py migrate 

