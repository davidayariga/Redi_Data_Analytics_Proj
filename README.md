# Redi_Data_Analytics_Proj

## Real Estate Price Analysis

## Problem Statement

This project aims to analyse and predict real estate prices based on various property features such as area, number of bedrooms, availability of amenities and furnishing status. By developing a linear regression model, this project aims to create a linear model that quantitatively relates house prices with variables such as number of rooms, area, number of bathrooms, etc. and to know the model's accuracy, i.e. how well these variables can predict house prices.

## Data

The dataset, Real Estate.csv, which was obtained from Kaggle contains 545 records of real estate properties with the following attributes:

•	Numerical Features: price, area, bedrooms, bathrooms, stories, parking.

•	Binary Categorical Features: mainroad, guestroom, basement, hotwaterheating, airconditioning, prefarea (values: yes/no).

•	Non-Binary Categorical Feature: furnishingstatus (values: furnished, semi-furnished, unfurnished).

## Analysis

## Data Preparation:

o	Binary categorical variables were encoded as 1 (yes) or 0 (no).

o	The non-binary categorical variable ‘furnishingstatus’ was one-hot encoded, with one category dropped to avoid multicollinearity.

The data was split into training and testing sets.

## Model Building:

A linear regression model was trained on the processed data using price as the target variable and all other columns as features.

## Evaluation:

o	The model was evaluated using metrics such as R-squared (R²).
o	The results showed a R² score of 0.653, indicating that the model explains approximately 65.3% of the variance in property prices.

## Conclusion

The linear regression model provides a reasonable approximation for predicting property prices based on the given features. However, the relatively high MSE suggests there may be room for improvement, such as:

•	Including additional relevant features.

•	Exploring advanced regression techniques or non-linear models.

•	Addressing potential outliers or feature scaling issues.

This project demonstrates the practical application of data preprocessing, feature engineering and regression modelling in the real estate domain.

## Resources and Bibliography

Google Colab as the coding environment with help from Gemini and Chatgpt

Microsoft Machine Learning for Engineers available at https://github.com/microsoft/ML-For-Beginners 

Kaggle introduction to Machine Learning available at https://www.kaggle.com/learn/intro-to-machine-learning

