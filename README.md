# Karra's Food — FastAPI Website

## Setup

1. Install dependencies:
   pip install -r requirements.txt

2. Run the server:
   python main.py

4. Open your browser at http://localhost:8000

## Structure

- main.py           FastAPI app with all routes and menu data
- templates/        Jinja2 HTML templates
- static/css/       Stylesheet
- static/js/        JavaScript (navbar scroll, mobile menu, scroll reveal)

## Pages

- /           Homepage with hero, welcome, featured dishes
- /menu       Full menu (Starters, Mains, Desserts, Drinks)
- /about      Story, values, team
- /contact    Reservation form with server-side validation
