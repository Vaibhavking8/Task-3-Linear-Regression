# Task-3-Linear-Regression

This project demonstrates how to predict housing prices using a Linear Regression model with the `Housing.csv` dataset.

## Steps Followed

1. **Import and Preprocess the Dataset**
   - Loaded the dataset using pandas.
   - Applied one-hot encoding to convert categorical variables into numerical format.

2. **Train-Test Split**
   - Split the dataset into training and testing sets (80% train, 20% test).

3. **Model Training**
   - Trained a Linear Regression model using `sklearn.linear_model.LinearRegression`.

4. **Model Evaluation**
   - Evaluated the model using:
     - Mean Absolute Error (MAE)
     - Mean Squared Error (MSE)
     - R² Score: 0.653

5. **Visualization**
   - Plotted the regression line for a single feature (`area`) against price.
   - Interpreted the regression coefficients.
