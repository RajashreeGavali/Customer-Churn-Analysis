# Telco Customer Churn Analysis
## Project Overview
This project analyzes the Telco Customer Churn dataset to identify key factors contributing to customer churn and build predictive models to forecast future churn. The dataset contains information about customer demographics, account details, and services they've subscribed to. The goal is to provide actionable insights and strategies to help reduce churn.

## Dataset
The dataset used in this analysis is the Telco Customer Churn dataset from Kaggle. It contains the following key features:

Customer demographics (gender, seniority, etc.)
Account information (tenure, monthly charges, contract type, etc.)
Subscription services (internet service, phone service, etc.)
Churn status (whether the customer has churned or not)
### Dataset:
Kaggle - Telco Customer Churn Dataset

## Project Workflow
### 1. Data Exploration (Excel)
Loaded the dataset into Excel for an initial exploration.
Checked for missing values and handled them by removing or imputing where necessary.

Created Pivot Tables to summarize key metrics such as:

Average Tenure

Monthly Charges

Churn Rate by gender, contract type, and other categories.
Used basic charts (e.g., bar charts, pie charts) to visualize key insights.

### 2. Data Preprocessing (Python)
Imported the dataset into Python using pandas.
Performed one-hot encoding on categorical variables to make them suitable for machine learning models.

Standardized numerical features like Monthly Charges and Tenure for model consistency.

### 3. Exploratory Data Analysis (Python)
Used pandas, matplotlib, and seaborn to explore relationships between features and churn.
Calculated correlations and created heatmaps to identify the most important features contributing to churn.
Visualized the distribution of churn across key variables (contract type, payment method, etc.).

### 4. Model Building
Split the data into training and testing sets.
Built a Logistic Regression model as the baseline model to predict customer churn.
Also explored other models such as:
Decision Trees
Random Forests

### 5. Model Evaluation
Evaluated model performance using the following metrics:
Accuracy
Precision
Recall
F1 Score
Confusion Matrix
Calculated the ROC-AUC score to assess model performance.
Compared the performance of the Logistic Regression model with Decision Trees and Random Forests to identify the best model.

### 6. Key Findings
Identified important factors contributing to customer churn, such as:
Contract Type: Month-to-month customers are more likely to churn.
Tenure: Customers with shorter tenure are more likely to churn.
Monthly Charges: Higher monthly charges are associated with higher churn.
Predictive Model: The best-performing model helps identify customers at risk of churning, enabling targeted retention strategies.
### 7. Recommendations
Offer personalized contract renewals or discounts for long-tenure customers.
Improve customer service for high-risk customer segments.
Implement targeted marketing campaigns based on churn risk.

## Tools & Libraries Used
## Excel:

Pivot Tables

VLOOKUP

Basic charts for initial data exploration

## Python:

### pandas: Data loading, cleaning, and preprocessing
### numpy: Numerical operations
### scikit-learn: Model building and evaluation
### matplotlib: Data visualization
### seaborn: Advanced data visualization

# Conclusion
This project provides a detailed analysis of the factors driving customer churn and builds a predictive model that can help identify at-risk customers. The findings offer actionable insights and recommendations to reduce churn and enhance customer retention strategies.
