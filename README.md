# Melbourne Housing Price Prediction

## Project Overview

This project focuses on predicting house prices in Melbourne, Australia, using Machine Learning regression algorithms. The dataset is cleaned, preprocessed, and analyzed before training multiple models to compare their predictive performance.

## Dataset

The dataset contains housing information from Melbourne, including property features, location-related details, and house prices.

## Data Preprocessing

- Handled missing values
- Removed duplicate records
- Detected and handled outliers using the IQR method
- Extracted Year and Month from the Date column
- Encoded categorical variables
- Performed feature selection
- Applied feature scaling for KNN

## Machine Learning Models

Five regression algorithms were implemented and evaluated:

- Linear Regression
- Random Forest Regressor
- XGBoost Regressor
- Decision Tree Regressor
- K-Nearest Neighbors (KNN)

## Model Evaluation

The models were evaluated using the following regression metrics:

- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

Model performance was compared using an R² score visualization and Actual vs Predicted plots.

## Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- XGBoost
- Google Colab / Jupyter Notebook

## Results

XGBoost Regressor achieved the highest R² score among the five models tested, with approximately **0.78 on the test set**.

## Conclusion

This project compares different regression algorithms for Melbourne housing price prediction. Based on the evaluation results, XGBoost Regressor performed best among the models tested.
