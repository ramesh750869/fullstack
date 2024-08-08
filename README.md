# fullstack

Steps to run backend in Python:


Create Virtual environment-
python3 -m venv venv
source venv/bin/activate

Project structure-
flask_app/
├── app.py
├── models.py
├── config.py


Create and Access Postgres Database:

CREATE DATABASE fullstack_test;


Create a user and grant privileges:

CREATE USER username WITH PASSWORD 'password';
GRANT ALL PRIVILEGES ON DATABASE fullstack_test TO username;




