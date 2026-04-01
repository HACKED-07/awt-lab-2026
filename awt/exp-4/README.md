# Experiment 4: Django Authentication Lab

This experiment mirrors the simple authentication flow from `AWT/myproject` using Django's built-in user system.

## Features

- login page at `/`
- protected home page at `/home/`
- logout route at `/logout/`
- SQLite database for storing Django auth users

## Run

1. Create and activate a virtual environment.
2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Apply migrations:

```bash
python manage.py migrate
```

4. Create a user:

```bash
python manage.py createsuperuser
```

You can also create a normal user from the Django shell if you prefer.

5. Start the server:

```bash
python manage.py runserver
```

6. Open `http://127.0.0.1:8000`

## Notes

- This lab keeps the flow intentionally minimal so the authentication logic is easy to follow.
- It uses Django's built-in `authenticate`, `login`, and `logout` helpers.
