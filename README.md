# Keras & Flask Classifier Web App
A minimum implementation of image classifier web app with Keras & Flask

## Setup
1. Clone this repository, and from within the root of the repo run the following:
2. `python3.7 -m venv venv`
3. `source venv/bin/activate`
4. `pip install -r requirements.txt`

## Usage
1. `python main.py`
2. Open `http://127.0.0.1:5000/` on your browser
3. Click the file select button and select one of the test images

## Demo
![demo](https://github.com/harupy/keras-flask-classifier/blob/master/demo.gif)

## Notes on upgrade from tf 1 to tf 2
* It is necessary to retrain the model and save with tf2. Using the original tf1 model with tf2 raises error `AttributeError: 'list' object has no attribute 'items'`
