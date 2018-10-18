<h1>Chapter1 Installations</h1>
Creatign the Working Directory (Open Command Prompt on your working location)

$ mkdir flasky $ cd flask

Creating a Virtual Environment with Python 3

$ python -m venv virtual-environment-name The -m venv option runs the venv package from the standard library as a standalone script, passing the desired name as an argument.

Working with a Virtual Environment The environment activation command $ venv\Scripts\activate

Installing Python Packages with pip

(venv) $ pip install flask

Check installed packages

(venv) $ pip freeze

