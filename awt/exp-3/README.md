# Experiment 3: Flask Authentication Lab

This experiment builds a simple Flask authentication flow with:

- user registration
- login with session handling
- a protected dashboard
- logout
- SQLite storage for user records

## Run

1. Create and activate a virtual environment.
2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Start the app:

```bash
python app.py
```

4. Open `http://127.0.0.1:5000`

## Note

This keeps the same lab idea as the other repository's Flask project, but uses a different code structure:

- direct `sqlite3` access instead of SQLAlchemy
- Flask sessions instead of Flask-Login
- hashed passwords instead of storing plain text passwords
