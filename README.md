# Car Price Prediction Using Multiple Linear Regression

## Project Overview

This project predicts the price of a car based on various features such as size, weight, engine performance, and fuel efficiency. It demonstrates an end-to-end workflow of data preprocessing, feature engineering, modeling, and evaluation.

## Dataset

Source: Car Price dataset (CSV format)

Features: Numerical and categorical attributes including:

Size & Weight: wheelbase, carlength, carwidth, carheight, curbweight

Engine & Performance: enginesize, horsepower, boreratio, stroke, compressionratio, peakrpm

Fuel Efficiency: citympg, highwaympg

Categorical (encoded): fueltype, aspiration, doornumber, carbody, drivewheel, enginelocation, fuelsystem

## Workflow

### 1. Exploratory Data Analysis (EDA)

Understanding distributions, relationships, and missing values

### 2. Preprocessing

Label Encoding for binary features

One-Hot Encoding for nominal categorical features

Dropping non-useful columns

### 3. Feature Selection

Selecting features that influence car price significantly

### 4. Modeling

Train-test split (80:20)

Multiple Linear Regression model

### 5. Evaluation

R² Score and RMSE for model performance

Scatter plot of actual vs predicted prices

## Results

R² Score: **[0.86]**

RMSE    : **[3793.54]**
## Conclusion

Features like enginesize, horsepower, curbweight, and car dimensions strongly influence car price.

The model can predict car prices with reasonable accuracy for the given dataset.

## How to Run

1. Clone the repository

2. Open the Jupyter Notebook: `CarPricePredict\_MLR.ipynb`

3. Ensure the dataset is in the `data/` folder

4. Run the notebook cells step by step



#### Author
#### Ajithkumar

Data Science Enthusiast | Healthcare Operations Professional | Python & SQL Learner

