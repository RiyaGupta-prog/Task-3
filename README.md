💻Housing Price Prediction using Linear Regression

This project predicts house prices based on various features using a Linear Regression model in Python.

📁 Dataset

•File: Housing.csv

•Target Variable: price

Features:

•area (in sq.ft)

•bedrooms, bathrooms, stories, parking

•Binary categorical: mainroad, guestroom, basement, hotwaterheating, airconditioning, prefarea

•Multi-class categorical: furnishingstatus



✅ Steps Covered

1. Data Preprocessing

•Converted binary categorical variables (yes/no) to 1/0.

•One-hot encoded the furnishingstatus column.

•Checked for and handled missing values.


2. Train-Test Split

•Used train_test_split() to split the dataset (80% train, 20% test).


3. Model Training

•Applied Linear Regression using sklearn.linear_model.LinearRegression().


4. Evaluation Metrics

•Mean Absolute Error (MAE)

•Mean Squared Error (MSE)

R² Score


5. Coefficient Analysis

•Extracted and displayed model coefficients to understand feature importance.


6. Visualization

•Plotted regression line for area vs price to visualize prediction fit.


📦 Requirements

pip install pandas numpy matplotlib seaborn scikit-learn

🚀 How to Run

python housing_price_prediction.py

Or use a Jupyter Notebook/Google Colab for step-by-step execution and visual output.

📌 Notes

•Linear Regression assumes a linear relationship between independent variables and the target.

You can experiment with Polynomial Regression or feature scaling to enhance results.




Author: Riya Gupta 
Internship Task 3: Linear Regression
