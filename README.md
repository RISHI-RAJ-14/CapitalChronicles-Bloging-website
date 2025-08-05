# Sample2 Django Project

This is a Django project configured for deployment on Vercel.

## Features

- Django 5.2+
- CKEditor integration (`django-ckeditor`)
- Production-ready WSGI server (`gunicorn`)
- Static file serving with `whitenoise`

## Setup

1. **Clone the repository:**
   ```sh
   git clone <your-repo-url>
   cd sample2
   ```

2. **Install dependencies:**
   ```sh
   pip install -r requirements.txt
   ```

3. **Apply migrations:**
   ```sh
   python manage.py migrate
   ```

4. **Run locally:**
   ```sh
   python manage.py runserver
   ```

## Deployment on Vercel

- Ensure you have a `vercel.json` configuration file.
- Set up
