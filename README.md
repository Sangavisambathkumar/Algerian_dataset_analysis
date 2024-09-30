# Algerian_dataset_analysis

This project aims to analyze and predict forest fires in Algeria using various machine learning techniques. It leverages datasets related to weather conditions, fire indices, and environmental factors to build predictive models that can assist in preventing and managing wildfires.Wildfires are a growing environmental concern, especially in regions with dry climates like Algeria. This project uses historical weather data to develop machine learning models that can predict the occurrence and severity of forest fires.

Data Description
The dataset used in this project includes the following features:

Temperature: Ambient temperature (in degrees Celsius)
Relative Humidity (RH): Measured as a percentage
Wind Speed (Ws): Measured in km/h
Rain: Amount of rain (in mm)
Various fire indices like FFMC, DMC, DC, ISI, BUI, and FWI
The target variable is the occurrence and intensity of forest fires.

Usage
Data Preparation:

Load the dataset and clean the data as necessary.
Split the data into training and testing sets using train_test_split.
Model Training:

Train various regression models like Linear Regression, Ridge Regression, and Lasso Regression.
Evaluate the models using cross-validation and calculate performance metrics like Mean Squared Error (MSE) and R² Score.
Prediction:

Use the trained models to make predictions on the test set.
Visualize the results and compare the performance of different models.
You can run the notebook file (Algerian_forest_fire.ipynb) to see the detailed steps for data exploration, model building, and evaluation.
