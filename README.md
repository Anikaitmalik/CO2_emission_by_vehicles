# CO2 Emission by Vehicles

This project analyzes CO2 emissions by vehicles using a dataset provided by the Canadian Government. The dataset captures how CO2 emissions vary with different vehicle features over a period of 7 years. The dataset is available on [Kaggle]( https://www.kaggle.com/datasets/debajyotipodder/co2-emission-by-vehicles)

## Project Description

This project aims to explore and analyze the CO2 emissions from various vehicles using different regression models. The analysis includes data cleaning, exploratory data analysis (EDA), handling outliers, and model evaluation. The final goal is to identify the best model for predicting CO2 emissions based on vehicle features.

## Dataset

The dataset includes information on the following attributes:
- **Model**: Type of vehicle drive (e.g., 4WD, AWD, etc.)
- **Transmission**: Type of transmission and number of gears (e.g., A, AM, etc.)
- **Fuel Type**: Type of fuel used (e.g., regular gasoline, diesel, etc.)
- **Fuel Consumption**: City, highway, and combined fuel consumption ratings in litres per 100 kilometres (L/100 km) and miles per imperial gallon (mpg)
- **CO2 Emissions**: Tailpipe emissions of carbon dioxide (in grams per kilometre)

## Features

### Data Cleaning
- Dropping irrelevant columns
- Handling missing values

### Feature Engineering
- Extracting transmission type and number of gears
- Converting fuel consumption units

### EDA (Exploratory Data Analysis)
- Visualizing distributions
- Checking for outliers

### Outlier Handling
- Using the IQR method to detect and replace outliers

### Model Building
- Implementing and evaluating multiple regression models:
  - Linear Regression
  - Lasso Regression
  - Ridge Regression
  - Decision Tree
  - Support Vector Regression (SVR)

### Model Evaluation
- Comparing models based on various metrics:
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)
  - R-squared (R²)
  - Mean Absolute Error (MAE)
  - Mean Absolute Percentage Error (MAPE)

