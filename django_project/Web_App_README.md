# Overview

I made a web app with the help from a few Youtube videos and the documentation from the django website. My web App is a blog style app that allows users to create an account and make posts to the websit for everyone to see. To start the server on your own machine open the command line and change your directory to the django_project folder under the Webapp_blog directory from there you will start the server by entering the command 'python manage.py runserver' (without the quotes). It will then show you where the server is running at the bottom of the terminal for example mine says 'Starting development server at http://127.0.0.1:8000/' you can also find the server at localhost:'enter the port number here' in my case it will be localhost:8000/ You can stop the server with CTRL + C.

[Software Demo Video](https://youtu.be/NlyeG-9YXAY)

# Web Pages

I made a few pages one is a login screen, I made a post screen where you can post something new on the blog and a home screen where you can see all of the posts that others have posted.

# Development Environment

I used django for the webframe for the website. 
The Youtube I watched showed me crispy_forms which can be installed by running this command in your terminal 'pip install django-crispy-forms'

# Useful Websites

* [Django documentation](https://www.djangoproject.com/)
* [Corey Schafer - Blog Web App Series](https://www.youtube.com/watch?v=UmljXZIypDc&list=PL-osiE80TeTtoQCKZ03TU5fNfx2UY6U4p)

# Future Work

* add forgot passwpord action to profile that will email the user.
* Add a Profile editer to change password.
* add the ability to add your own profile picture.