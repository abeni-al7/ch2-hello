# Hello World (Dockerized Django)

A minimal Django project that returns "Hello, World!" from a single view, containerized with Docker. Exercise from a Django book/course chapter on Docker.

## Features

- `pages` app with one function view returning an `HttpResponse`
- Runs via Docker Compose (`docker-compose up`) with code mounted into the container

## Built with

- Django 4.0
- SQLite
- Docker / Docker Compose (Python 3.10 slim base image)

## Run it

With Docker:

```bash
docker-compose up
```

Or locally:

```bash
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

Then visit http://127.0.0.1:8000/. Learning project.
