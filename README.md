the hosted website is at https://anime-club-iitb.herokuapp.com/


Setup: How to run it locally

The first thing to do is to clone the repository:

$ git clone https://github.com/SoC-Club-Website/final-website.git

$ cd final-website

Create a virtual environment to install dependencies in and activate it:

$ virtualenv2 --no-site-packages env

$ source env/bin/activate

Then install the dependencies:

(env)$ pip install -r requirements.txt

Note the (env) in front of the prompt. This indicates that this terminal session operates in a virtual environment set up by virtualenv2.

Once pip has finished downloading the dependencies:

(env)$ python manage.py runserver

And navigate to http://127.0.0.1:8000/
