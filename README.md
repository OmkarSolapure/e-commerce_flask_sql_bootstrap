# e-commerce_flask_sql_bootstrap
A single-page e-commerce web application built with Python (Flask), SQLite, and HTML/CSS/Bootstrap. Includes authentication, item management, and a shopping cart with persistence.

# Create virtual environment
python -m venv venv
venv\Scripts\activate   # (Windows)
# source venv/bin/activate   # (Linux/Mac)

# Install dependencies
pip install -r requirements.txt

# Seed database with sample items
python seed.py

# Start development server
python app.py
App will be live at 👉 http://127.0.0.1:5000
