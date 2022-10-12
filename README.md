# PCOS-Predictor-

Prerequisites:
Run pip install -r requirements.txt to install all the required libraries

Project Structure
This project has four major parts :

model.py - This contains code for our Machine Learning model to predict PCOS based on training data in 'pcos.csv' file.
app.py - This contains Flask APIs that receives PCOS details through GUI or API calls, computes the precited value based on our model and returns it.

Running the project
Run model.py - using python model.py - to create a machine learning model. This will create a serialized version of our model into a file model.pkl

Run app.py - using python app.py - to start Flask API

Navigate to URL http://localhost:5000

Enter valid numerical values in all input boxes and hit Predict.

If everything goes well, you should be able to see the predcited vaule on the HTML page
