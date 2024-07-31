Diabetes Prediction System
Project Overview
This project aims to predict the likelihood of a person having diabetes using machine learning techniques. The system utilizes a dataset of various health metrics to train a model which can then be used to make predictions based on new input data.

Repository Structure
Diabetes_prediction_system.ipynb: Jupyter notebook containing the entire workflow of data analysis, preprocessing, model training, evaluation, and prediction.
diabetes_predict.py: Python script for making predictions using the trained model.
diabetes.csv: Dataset containing the health metrics used for training the model.
diabetes_model (1).sav: Saved model file used for making predictions.
streamlit.txt.txt: Requirements file for setting up Streamlit application.
Files and Description
Diabetes_prediction_system.ipynb

Contains exploratory data analysis (EDA), data preprocessing, model building, and evaluation steps.
Includes visualizations and insights derived from the dataset.
diabetes_predict.py

Script to load the trained model and make predictions on new data inputs.
Can be used in a production environment to serve the model for real-time predictions.
diabetes.csv

The dataset used for training and testing the model.
Contains features like glucose levels, blood pressure, BMI, age, and other relevant health metrics.
diabetes_model (1).sav

Serialized version of the trained model.
Can be loaded for inference without retraining the model.
streamlit.txt.txt

Lists the required dependencies to run the Streamlit web application.
Streamlit is used to create an interactive web app for users to input their health data and get predictions.
Getting Started
Prerequisites
Python 3.x
Jupyter Notebook
Streamlit
Usage
The Jupyter Notebook provides a detailed walkthrough of the data analysis, model training, and evaluation processes.
The prediction script (diabetes_predict.py) can be used to make predictions on new input data.
The Streamlit application provides an interactive interface for users to input their data and receive predictions.
Model Training and Evaluation
The dataset is split into training and testing sets.
Several machine learning algorithms are tested, and the best-performing model is saved for future use.
Model performance is evaluated using metrics such as accuracy, precision, recall, and F1-score.
Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.



Contact
Rishitha Ballem - GitHub

