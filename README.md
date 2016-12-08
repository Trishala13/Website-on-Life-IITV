# Website-on-Life@IITV
Life@IITV Portal is an iteractive website where students can post information about their innovations, achievements, startups and internships/placements. 

## Dependencies
- Python 2.7
- Django 1.10
- SQLite

## Installation
1. Install Python 2.7. See [this](https://docs.python.org/2/using/index.html) for more details.
2. Install Django 1.10 using ``pip``:

        pip install django==1.10
  

## Usage
1. Create a superuser (admin) for handling the web app. `cd` to root of the project and enter in terminal:

        python manage.py makemigrations
        python manage.py migrate
        python manage.py createsuperuser
    
2. Enter your username, email and password.
3. Enter following in terminal to run server on localhost:
        
        python manage.py runserver

4. Visit [http://localhost:8000/life/home](http://localhost:8000/life/home) to view the app. Login to admin area [http://localhost:8000/admin](http://localhost:8000/admin) to create, manage, edit and delete posts. Create posts for different categories- achievements, Startup-fair and Placements.

## Contributors

  - Trishala Pugazhendhi
  - Ayushi Jain
  - Aakash Mallik
  - Deevashwer Rathee
