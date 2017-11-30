# Exploring Django Features

[![Python Version](https://img.shields.io/badge/python-3.6-brightgreen.svg)](https://python.org)
[![Django Version](https://img.shields.io/badge/django-1.11-brightgreen.svg)](https://djangoproject.com)


## Major Features
```bash
1. Login
```

```bash
2. Logout
```

```bash
3. Signup
```

```bash
4. URL Configuration
```

```bash
5. Humanize
```

```bash
6. Pagination
```

```bash
7. Account Management
```

```bash
8. Static Files, and templates.
```

## Running the Project Locally

First, clone the repository to your local machine:

```bash
git clone git@github.com:boazkipro/forum-django.git
```

Install the requirements:

```bash
pip install -r requirements.txt
```

Setup the local configurations:

```bash
cp .env.example .env
```

Create the database:

```bash
python manage.py migrate
```

Finally, run the development server:

```bash
python manage.py runserver
```

The project will be available at **127.0.0.1:8000/index**.

