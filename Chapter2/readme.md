
<h2>Chapter 2. Basic Application Structure</h2>

<h3>Initiallization</h3>
All Flask applications must create an application instance. 

from flask import Flask
app = Flask(__name__)

The only required argument to the Flask class constructor is the name of the
main module or package of the application.

<h3>Routes and View Functions</h3>

The most convenient way to define a route in a Flask application is through the
app.route decorator exposed by the application instance. 


@app.route('/')
def index():
return 'Hello World!'

the app.route decorator is the preferred method to register view functions

<b>Note:</b> The Flask development web server can also be started programmatically by invoking theapp.run() method. Older versions of Flask that did not have the flask command required the
server to be started by running the application’s main script, which had to include the
following snippet at the end:

<p>if __name__ == '__main__':</p>
app.run()

While the flask run command makes this practice unnecessary, the app.run() method can
still be useful on certain occasions
