#  Deploying Machine Learning models 

We'll use the same model we trained and evaluated
previously - the churn prediction model. Now we'll
deploy it as a web service.


## 1 Saving and loading the model

* Saving the model to pickle
* Loading the model from pickle
* Turning our notebook into a Python script

## 2 Web services: introduction to Flask

* Writing a simple ping/pong app
* Querying it with `curl` and browser

## 3 Serving the churn model with Flask

* Wrapping the predict script into a Flask app
* Querying it with `requests` 
* Preparing for production: gunicorn
