# Practical-Application-Assignment-11.1
Find out What Drives the Price of a Car


## Used Car Price Prediction 
### Project Overview
This project focuses on analyzing a dataset of used cars and identifying key factors that influence the price of a used car. The main goal is to provide a used car dealership with insights and recommendations on how to optimize their inventory based on what consumers value most in used vehicles.

### Key Objectives:
Business Understanding: From a business perspective, identify key drivers for used car prices.
Data Cleaning and Preprocessing: Prepare the dataset for modeling by handling missing values, outliers, and encoding categorical features.
Modeling: Use Linear Regression and Lasso Regression to predict used car prices and compare the models based on MAE and RMSE.
Evaluation and Recommendations: Evaluate the models and offer actionable recommendations for the dealership based on the findings.
### Dataset
The dataset contains information on various attributes of used cars such as:

Year of manufacture
Mileage (Odometer)
Manufacturer
Condition
Fuel type
Transmission type
And other relevant features
The dataset was cleaned to remove missing values, extreme outliers, and only include cars manufactured after the year 2000.

### Steps
#### 1. Data Cleaning
Removed rows with missing values.
Filtered out cars with prices less than or equal to zero.
Focused on cars manufactured after the year 2000.
Removed cars with odometer readings above 450,000 miles, as these were outliers.

#### 2. Feature Engineering
Selected important features such as year, manufacturer, condition, fuel type, and odometer.
Categorical variables were encoded using one-hot encoding.
Standardized the numerical features to ensure better model performance.

#### 3. Model Building
Two models were developed:

Linear Regression
Lasso Regression
Both models were trained on the processed dataset, and their performance was evaluated using:

Mean Absolute Error (MAE)
Root Mean Squared Error (RMSE)
#### 4. Results
Linear Regression MAE: X.xx
Linear Regression RMSE: X.xx
Lasso Regression MAE: X.xx
Lasso Regression RMSE: X.xx
Based on the comparison of MAE and RMSE, the better-performing model was chosen and used for final recommendations.

#### 5. Visualization
Several key visualizations were generated to support the findings, such as:

Price vs. Mileage: Showing the negative correlation between odometer reading and price.
Price vs. Year: Indicating that newer cars generally have higher prices.
Price vs. Fuel Type: Showing that electric and hybrid cars tend to have higher resale values.

### Recommendations
Based on the analysis and model results, the following recommendations are made to the dealership:

Focus on low-mileage cars: Higher mileage significantly reduces the resale value of a car.
Prioritize newer cars: Cars manufactured within the last five years tend to hold their value better.
Include premium brands: Brands like BMW, Mercedes, and Audi tend to retain higher market prices, attracting high-end buyers.
Consider eco-friendly options: Electric and hybrid vehicles have higher resale values, especially in markets with environmental concerns.
Ensure cars are in good condition: Cars in "excellent" or "like new" condition sell for higher prices.
