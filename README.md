# House Price Prediction API

Welcome to the House Price Prediction API project! This repository showcases a machine learning model built using FastAPI and scikit-learn, designed to predict house prices. The project highlights the entire process from data import to API deployment, providing a practical example of how to integrate machine learning models into other applications.

## Introduction

This project demonstrates the development and deployment of a house price prediction model. The model was built using scikit-learn pipelines and deployed as an API using FastAPI. The API can be used to predict house prices based on input features, making it a useful tool for integration into various applications.

## Project Overview

The project follows a typical machine learning workflow:

- **Data Import**: Loading the dataset required for model training.
- **Data Splitting**: Dividing the data into training and testing sets to evaluate model performance.
- **Exploratory Data Analysis**: Analyzing the data to understand its structure and relationships.
- **Data Preprocessing**: Preparing the data for modeling, including handling missing values and feature scaling.
- **Modeling**: Building regression models to predict house prices.
- **Evaluation**: Assessing model performance using various metrics.
- **Saving Models**: Storing the trained model for later use.
- **Building an API**: Creating a FastAPI-based API to serve the model and make predictions accessible.

## Prerequisites

Ensure you have the following installed:

- Python 3.x
- FastAPI
- scikit-learn
- pandas
- numpy
- Postman (for API testing)
- Heroku CLI (for deployment)

## Project Workflow

1. **Importing Data**  
   The first step involves importing the dataset containing house features and their corresponding prices. This data is used to train and evaluate the prediction model.

2. **Splitting Data into Training and Testing**  
   The dataset is split into two subsets: a training set used to fit the model, and a testing set used to evaluate the model's performance on unseen data.

3. **Exploratory Data Analysis**  
   Exploratory Data Analysis (EDA) is performed to understand the distribution of data, identify patterns, and discover potential relationships between features.

4. **Data Preprocessing**  
   Data preprocessing includes steps such as handling missing values, encoding categorical variables, and scaling features to ensure the data is ready for modeling.

5. **Modelling Regression Problems**  
   Several regression models are built and trained on the dataset. The goal is to identify the model that provides the most accurate predictions of house prices.

6. **Evaluation, Predictions, and Scoring**  
   The models are evaluated using metrics such as Mean Squared Error (MSE) and R-squared to determine their accuracy. Predictions are made on the test data, and the models' performance is scored.

7. **Saving Models**  
   The trained model is saved to disk, enabling it to be loaded and used for predictions without needing to retrain.

8. **Building a Machine Learning API**  
   Finally, a FastAPI-based API is built to serve the model. This API allows users to send requests with house features and receive price predictions in response. The API is tested using Postman, and deployed to Heroku using the Heroku CLI.

## License

This project is licensed under the MIT License. See the [LICENSE] file for more details.
