# Flask-Web-Development
Flask is a microframework for Python based on Werkzeug, Jinja 2 and good intention.
Flask is easy to set-up I am working on Windows so all codes and installaton setups are accordingly Windows 10


Chapter1 Installations:

Creatign the Working Directory (Open Command Prompt on your working location)

$ mkdir flasky
$ cd flask

Creating a Virtual Environment with Python 3

$ python -m venv virtual-environment-name
The -m venv option runs the venv package from the standard library as a
standalone script, passing the desired name as an argument.

Working with a Virtual Environment
The environment activation command 
$ venv\Scripts\activate

Installing Python Packages with pip

(venv) $ pip install flask

Check installed packages

(venv) $ pip freeze 

Chapter 2. Basic Application Structure

Initiallization
All Flask applications must create an application instance. 

from flask import Flask
app = Flask(__name__)

Routes and View Functions
