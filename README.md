# House Price Prediction System

## Overview
The **House Price Prediction System** is a machine learning-based web application that predicts house prices based on important property features such as area, number of bedrooms, bathrooms, stories, and parking availability.
This project demonstrates an end-to-end machine learning workflow, including data preprocessing, model training, model serialization, Flask backend development, frontend integration, and cloud deployment.

## Objectives
- Build a machine learning model to predict house prices
- Perform data preprocessing and feature selection
- Train and evaluate a regression model
- Save the trained model for future predictions
- Develop a Flask web application for user interaction
- Integrate the trained model with a frontend interface
- Deploy the project as a live web application

## Features
- Predicts house prices using a trained machine learning model
- User-friendly web interface
- Flask-based backend
- Real-time prediction output
- Responsive frontend design
- Trained model saved using Pickle/Joblib
- Clean and simple project structure
- Live deployment using Render

## Tech Stack
### Programming Language
- Python

### Machine Learning Libraries
- Pandas
- NumPy
- Scikit-learn
- Joblib

### Backend
- Flask
- Gunicorn

### Frontend
- HTML
- CSS
- JavaScript

### Deployment
- Render

### Version Control
- GitHub

## Project Structure
```text
HousePricePrediction/
│
├── app.py
├── train_model.py
├── train.csv
├── house_data.csv
├── model.pkl
├── requirements.txt
├── Procfile
├── README.md
│
├── static/
│   ├── style.css
│   └── script.js
│
└── templates/
    └── index.html
```

## Machine Learning Workflow
1. Load the dataset
2. Perform data cleaning and preprocessing
3. Select important features
4. Split data into training and testing sets
5. Train a regression model
6. Evaluate model performance
7. Save the trained model as `model.pkl`
8. Integrate the model with Flask
9. Take user input from the web interface
10. Display the predicted house price

## Input Features
The model predicts house prices using the following input features:
- Area
- Number of bedrooms
- Number of bathrooms
- Number of stories
- Parking availability
