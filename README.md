# Database Admin Tool

## App Info
    Name: Uber Fashions
    Desc: Backend database tool for Uber Fashions
    Version: 1.0
    Developer: Jessica Brock, jessicabrock03@gmail.com
    URL: https://fytkit.herokuapp.com

## Installation

    $ pip install pipenv
    $ cd my_project
    $ pipenv install
    $ pipenv shell

## Command line interface

    This project uses a few cli commands to create and edit the users

### Create user:

    $ pipenv run flask createuser

### Edit user:

    $ pipenv run flask changepassword

### Delete user:

    $ pipenv run flask deleteuser

## Local Server

    $ gunicorn server:app

    You should see a url you can copy/paste into your web browser.
    Example, http://127.0.0.1:8000
