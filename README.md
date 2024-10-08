# Diabetes Prediction System using Flask and Machine Learning

This project is a web-based **Diabetes Prediction System** built with Flask. It uses a machine learning model (trained using features like fasting sugar and frequent urination) to predict whether a user is at risk of diabetes or not.

## Features

- Accepts user inputs like **Fasting Sugar** and **Frequent Urination** to make predictions.
- The machine learning model is loaded using `pickle` for efficient inference.
- Provides user-friendly feedback based on the prediction.
- Simple web interface for interaction with the machine learning model.

## Technologies Used

- **Flask** - Web framework to create the backend and serve web pages.
- **Machine Learning Model** - Pretrained model loaded with `pickle` for predictions.
- **HTML** - Frontend templates for displaying results and forms.
- **scikit-learn** (for training the model).

## Machine Learning Model

The model is built using the following features:
- **Fasting Sugar**: An integer input representing the fasting blood sugar level.
- **Frequent Urination**: An integer value representing the frequency of urination.

The model was trained using a dataset (details of the dataset and model can be added here). The model is saved and loaded using the `pickle` library.
