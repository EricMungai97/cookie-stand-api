# LAB - Class 34

## Project: cookie-stand-api

## Author: Eric Mungai Kinuthia

## About

This app includes a frontend site that displays data about cookie stands. It also supports a Django REST Api. It uses a PostgreSQL database supplied by ElephantSQL.

## Links and Resources

[Deployed Server](https://cookie-stand-api-nine.vercel.app/)

[ElephantSQL](https://www.elephantsql.com/)

## Setup

* Requires a .env

## How to initialize

* Clone and cd into directory.

* Create venv by running `python3.11 -m venv .venv`

* Activate venv `source.venv/bin/activate`

* Install requirements by running `pip install -r requirements.txt`

* Then run `gunicorn project.wsgi:application --bind 0.0.0.0:8000 --workers 4` or `python manage.py runserver`

* To run inside container run `docker compose up`


