E-commerce Furniture Dataset 2024 – Data Analysis & Sales Prediction

Project Overview:
This project analyzes an e-commerce furniture dataset scraped from AliExpress to understand pricing patterns, shipping tags, and their impact on product sales. 
The project includes data cleaning, exploratory data analysis (EDA), feature engineering, and machine learning models to predict the number of items sold.

Objectives:
Analyze furniture product pricing and sales trends
Study the impact of shipping tags on sales
Perform exploratory data analysis (EDA)
Prepare features for machine learning
Build and evaluate regression models to predict sales

Tools & Technologies:
Python
Google Colab
Pandas – data manipulation
NumPy – numerical operations
Matplotlib – data visualization
Seaborn – advanced visualizations
Scikit-learn – machine learning models

Dataset Description
The dataset contains 2,000 furniture products scraped from AliExpress.
Columns:
| Column Name   | Description                    |
| ------------- | ------------------------------ |
| productTitle  | Name of the furniture item     |
| originalPrice | Original price before discount |
| price         | Current selling price          |
| sold          | Number of units sold           |
| tagText       | Shipping or promotional tag    |

Data Preprocessing:
Dropped originalPrice due to excessive missing values
Handled missing values in tagText
Cleaned price column by removing $ and ,
Encoded categorical variables using LabelEncoder

Exploratory Data Analysis (EDA)
The following analyses were performed:
Distribution of product prices
Distribution of items sold
Shipping tag frequency analysis
Relationship between price and number of items sold

Visualizations:
Count plots
Histograms
Scatter plots
Pair plots (filtered data)

Feature Engineering:
Converted tagText into numerical form
Selected relevant numerical features:
        price
        tagText

Machine Learning Models:

Two regression models were trained:
Linear Regression
Random Forest Regressor

Model Evaluation Metrics:
Mean Squared Error (MSE)
R² Score
Random Forest performed better due to non-linear relationships in data.

Key Insights:
Free shipping dominates the dataset
Lower-priced products tend to sell more
Shipping tags influence sales volume
Random Forest captures pricing-sales patterns better than Linear Regression

Project Structure:
Ecommerce-Furniture-Analysis/
│
├── ecommerce_furniture_dataset_2024.csv
├── Ecommerce_Furniture_Analysis.ipynb
├── README.md

Conclusion:
This project demonstrates a complete data analytics and machine learning workflow, from raw data cleaning to predictive modeling.
The insights gained can help e-commerce businesses optimize pricing strategies and improve sales performance.
