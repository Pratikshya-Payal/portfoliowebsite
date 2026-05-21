# portfoliowebsite# My Portfolio

A simple Django portfolio website built with Django 4.2.27.

## Project Structure

- `manage.py` - Django project management script
- `portfolio/` - Django project configuration
- `main/` - Django app for the portfolio site
- `templates/` - HTML templates
- `static/` - Static assets like CSS and images
- `db.sqlite3` - SQLite database file

## Requirements

- Python 3.x
- Django 4.2.27

## Setup

1. Create and activate a virtual environment:
   ```bash
   python -m venv .venv
   .\.venv\Scripts\activate
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run database migrations:
   ```bash
   python manage.py migrate
   ```
4. Start the development server:
   ```bash
   python manage.py runserver
   ```

## Usage

Open `http://127.0.0.1:8000/` in your browser to view the portfolio site.

## Notes

- The `templates/index.html` file contains the main homepage layout.
- Static CSS is located in `static/css/style.css`.

## License

This project is provided as-is.
