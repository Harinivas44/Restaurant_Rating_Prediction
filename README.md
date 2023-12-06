# Restaurant Rating Prediction 🍽️🌟

## Overview 🌐
In this project, we aimed to predict restaurant ratings based on various features such as online order availability, booking table options, votes, location, restaurant type, cuisine, and cost. We explored and cleaned the data, performed exploratory data analysis (EDA), and built machine learning models for prediction.

## Features 📊
- **Online Order:** Whether the restaurant offers online ordering (1 for Yes, 0 for No)
- **Book Table:** Whether the restaurant allows table booking (1 for Yes, 0 for No)
- **Votes:** Number of votes received by the restaurant
- **Location:** Numerical representation of restaurant location
- **Restaurant Type:** Numerical representation of the type of the restaurant
- **Cuisine:** Numerical representation of the cuisine offered by the restaurant
- **Cost:** Approximate cost for two people
- **Type:** Numerical representation of the service type (e.g., Delivery, Dine-out)

## Data Cleaning and EDA 🧹📈
- Cleaned missing values, duplicates, and unnecessary columns.
- Converted 'rate' and 'cost' columns to appropriate numerical formats.
- Explored average restaurant ratings, top-rated restaurants, and average votes received.
- Analyzed distribution and frequency of restaurant features.
- Visualized the distribution of approximate cost and restaurant types.

## Machine Learning Models 🤖📉
### Linear Regression Model
- Trained a Linear Regression model and evaluated performance.
- R2 Score: 0.22
- RMSE: 0.38

### XGBoost Regression Model
- Trained an XGBoost Regression model with tuned hyperparameters.
- Achieved significantly better performance.
- R2 Score: 0.95
- RMSE: 0.10

## Conclusion 🎉
The XGBoost Regression model outperformed the Linear Regression model, indicating its effectiveness in predicting restaurant ratings. The scatter plot visually demonstrates the accuracy of the predictions.

