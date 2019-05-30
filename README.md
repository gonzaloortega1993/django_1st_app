# Polls App / Django

## App made following the steps of the official Django Tutorial

This repository

Polls is a simple Django app to conduct Web-based polls. For each question, visitors can choose between a fixed number of answers.

I've created a `superuser`named `admin2` whose password is also `admin2` (xD), you will need it for the Admin app.

## Quick start

1. In the terminal go to mysite directory and activate the virtual environment `source env/bin/activate `, if django isn't installed you can do it with command `pip3 install django`

2. Start the server `python manage.py runserver`

3. Visit http://127.0.0.1:8000/admin/ to create a poll (you'll need the Admin app enabled).

4. Visit http://127.0.0.1:8000/polls/ to participate in the poll.

5. If you create a new app include it in URLconf in your project urls.py like this:

    path('polls/', include('polls.urls')),

6. Run `python manage.py migrate`



### Tools: python, pip3, virtualenv

