# House Price Distribution

This project explores housing data to understand price distributions, detect influential factors, and build a predictive model using linear regression. The workflow includes data cleaning, exploratory data analysis (EDA), preprocessing, model training, evaluation, and visualization — all aimed at predicting house prices based on features like area, number of bedrooms, and furnishing status.

# Project Structure

House_prices_distribution.ipynb
Housing.csv
README.md

# Objectives
Understand the distribution of house prices.
Identify key factors affecting house pricing.
Build a regression model using LinearRegression() to predict house prices.
Visualize actual vs predicted values using both seaborn and Plotly.

# Technologies Used
Python
Pandas, NumPy – data manipulation
Seaborn, Matplotlib, Plotly Express – data visualization
Scikit-learn – model building and evaluation

# Key Steps Performed
Data Loading
Read the housing dataset and examined structure with .info() and .describe().
Exploratory Data Analysis (EDA)
Visualized distributions, boxplots, and scatter plots.
Checked for skewness, outliers, and correlations.
Data Cleaning
Removed duplicates.
Handled missing values.
Encoded categorical variables (OneHot/LabelEncoder).
Model Training
Applied train_test_split().
Trained a LinearRegression() model on preprocessed data.
Evaluation Metrics
Mean Absolute Error (MAE)
Mean Squared Error (MSE)
Root Mean Squared Error (RMSE)
R² Score
Visualization of Results
Plotted actual vs predicted prices.

# Links
https://www.kaggle.com/datasets/yasserh/housing-prices-dataset
