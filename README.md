# OIBSIP_DataScience_Task3_Car_Price_Prediction

## Objective
Predict used car selling price using machine learning models (Linear Regression and Random Forest).

## Steps Performed
1. Data loading & initial inspection
2. Data cleaning & feature engineering (car age, encoding categorical variables)
3. Exploratory Data Analysis (visualizations)
4. Model training: Linear Regression and Random Forest
5. Model evaluation and feature importance

## Tools & Libraries
- Python 3
- pandas, numpy, matplotlib, seaborn
- scikit-learn
- joblib (optional for model saving)

## Outcome
The machine learning model successfully predicted car selling prices based on features such as brand, year of purchase, fuel type, seller type, transmission, and kilometers driven.
    The final Random Forest Regression model achieved:
        R² Score: ~0.96 (indicating a very high correlation between predicted and actual prices)
        Mean Absolute Error (MAE): around ₹50,000–₹80,000 depending on test split
The model demonstrated strong generalization and can be integrated into a web or desktop app for real-world car price estimation.

## Requirements
pandas , numpy , matplotlib , seaborn , scikit-learn , joblib , nbformat
