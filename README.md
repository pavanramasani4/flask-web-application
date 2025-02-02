# Flask Web Application

## Overview

This project is a Flask web application that allows users to sign up, log in, and manage their sessions. It uses a SQLite database to store user information and Flask-WTF for form handling and validation.

## Project Structure

```plaintext
MyProjectGroup/
│
├── static/
│   ├── home-styles.css
│   └── styles.css
├── templates/
│   ├── home.html
│   ├── index.html
│   ├── login.html
│   ├── signup.html
│   └── user.html
└── Week1.py

Prerequisites
 └── Python 3.9 or higher

Installation
Follow these steps to set up and run the application locally without Docker.

1. Clone the Repository
git clone https://github.com/your-username/my-flask-app.git  #Replace "your-username" with your GitHub username.
cd my-flask-app

2. Create and Activate a Virtual Environment
python -m venv venv  #For Windows
(Or)
venv\Scripts\activate #For macOS/Linux:

source venv/bin/activate

3. Install Dependencies
pip install -r requirements.txt

4. Set Up the Database
The application uses SQLite. The database will be created automatically when you run the app for the first time.

5. Run the Application
python Week1.py  #The application will start running on http://localhost:5000.

Running the Application 
Open your web browser and navigate to http://localhost:5000 to access the application.
