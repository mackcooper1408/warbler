# Warbler

# About the Application

This is a simple Twitter clone where users can make accounts, follow one another, engage in direct messages and, most importantly, warble their thoughts to the world.

This repository contains a flask application that serves HTML via jinja templates (deployed on Heroku).

## [Live Demo](https://warbler2000.herokuapp.com/)

## Setting up the development server

1. clone the repository
2. `cd warbler`
3. `python3 -m venv venv`
4. `source venv/bin/activate`
5. `pip install -r requirements.txt`

## Setting up the database
1. `createdb warbler`
2. `python seed.py`

## Starting the development server
1. `flask run`
#### server will start up at http://localhost:5000/

