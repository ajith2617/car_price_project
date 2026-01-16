# Car Price Predict



\# Car Price Prediction Using Multiple Linear Regression



\## Project Overview

This project predicts the price of a car based on various features such as size, weight, engine performance, and fuel efficiency. It demonstrates an end-to-end workflow of data preprocessing, feature engineering, modeling, and evaluation.



\## Dataset

\- Source: Car Price dataset (CSV format)

\- Features: Numerical and categorical attributes including:

&nbsp; - Size \& Weight: wheelbase, carlength, carwidth, carheight, curbweight

&nbsp; - Engine \& Performance: enginesize, horsepower, boreratio, stroke, compressionratio, peakrpm

&nbsp; - Fuel Efficiency: citympg, highwaympg

&nbsp; - Categorical (encoded): fueltype, aspiration, doornumber, carbody, drivewheel, enginelocation, fuelsystem



\## Workflow

1\. \*\*Exploratory Data Analysis (EDA)\*\*

&nbsp;  - Understanding distributions, relationships, and missing values

2\. \*\*Preprocessing\*\*

&nbsp;  - Label Encoding for binary features

&nbsp;  - One-Hot Encoding for nominal categorical features

&nbsp;  - Dropping non-useful columns

3\. \*\*Feature Selection\*\*

&nbsp;  - Selecting features that influence car price significantly

4\. \*\*Modeling\*\*

&nbsp;  - Train-test split (80:20)

&nbsp;  - Multiple Linear Regression model

5\. \*\*Evaluation\*\*

&nbsp;  - R² Score and RMSE for model performance

&nbsp;  - Scatter plot of actual vs predicted prices



\## Results

\- R² Score: \*\[0.8177069544523099]\*

\- RMSE: \*\[3793.5400345763105]\*



\## Conclusion

\- Features like enginesize, horsepower, curbweight, and car dimensions strongly influence car price.

\- The model can predict car prices with reasonable accuracy for the given dataset.



\## How to Run

1\. Clone the repository

2\. Open the Jupyter Notebook: `CarPricePredict\_MLR.ipynb`

3\. Ensure the dataset is in the `data/` folder

4\. Run the notebook cells step by step



\## Author

\- Ajithkumar



