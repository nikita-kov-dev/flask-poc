# Project Setup

* Install [Python3](https://www.python.org/downloads/)
* Install [Flask](https://flask.palletsprojects.com/en/stable/): ```pip install Flask```

# Helpful commands:
* Run the project: ```export FLASK_APP=app.py && export FLASK_ENV=development && flask run``` (http://127.0.0.1:5000/)
* Build docker image: ```docker build --tag flask-docker .```
* Run docker image: ```docker run -d -p 5000:5000 flask-docker```