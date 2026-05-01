# Flask-Auth-App
Flask-based web application with user authentication (login/signup) and template rendering

# Flask Auth & Weather App

A Flask-based web application with user authentication (signup/login) and a weather information feature using an external API.

## Features
- User registration and login system with MySQL database  
- Secure form handling using Flask (POST requests)  
- Weather data fetching using OpenWeather API  
- Dynamic HTML rendering using Jinja templates  

## Tech Stack
- Python (Flask)  
- MySQL (pymysql)  
- HTML, Bootstrap (UI)  
- REST API (OpenWeather)

## Project Structure
- app.py – main backend logic  
- templates/ – HTML templates (login, signup, home)  
- requirements.txt – dependencies  

## How to Run
1. Install dependencies:
   pip install -r requirements.txt  

2. Setup MySQL database:
   - Create database: python_157  
   - Create table: users(username, password)

3. Run the app:
   python app.py  

4. Open:
   http://127.0.0.1:5000/
