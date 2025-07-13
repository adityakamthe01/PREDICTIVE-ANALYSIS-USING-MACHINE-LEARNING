# PREDICTIVE-ANALYSIS-USING-MACHINE-LEARNING

*COMPANY* : CODTECH IT SOLUTIONS

*NAME* : ADITYA KAMTHE

*INTERN ID* : CT06DF2353

*DOMAIN* : DATA ANALYTICS

*DURATION* : 6 WEEKS

*MENTOR* : NEELA SANTOSH

## Predictive Analysis Using Machine Learning – Walmart Instagram Dataset

# Overview
This project titled "Predictive Analysis Using Machine Learning" demonstrates how machine learning models can be used to predict user engagement on Instagram posts using Walmart's Instagram data. The analysis was carried out on Google Colab, leveraging libraries such as Pandas, scikit-learn, Seaborn, and Matplotlib. The dataset was downloaded from Kaggle, and preprocessing, training, evaluation, and visualization steps were all completed within an interactive Colab environment.

# Objective
The primary objective of this project is to predict the number of Follows an Instagram post receives based on other available metrics like Likes, Impressions, Shares, Saves, and Profile Visits. This allows marketing teams to understand which factors influence follower growth and optimize content strategy accordingly.

# Dataset
Source: Kaggle

File Used: Instagram data.csv

Organization: Walmart

Features: Caption, Hashtags, Likes, Impressions, Shares, Saves, Profile Visits, Follows

The dataset includes Instagram engagement metrics from Walmart’s official account. It captures user interactions on posts and helps explore relationships between different engagement types.

Technologies Used
Platform: Google Colab

Language: Python

Libraries:

pandas – for data handling

scikit-learn – for model building and evaluation

matplotlib & seaborn – for data visualization

# Project Workflow
1. Environment Setup
Required Python packages were installed using pip in the Colab environment.

2. Data Loading and Cleaning
The dataset was loaded using pandas.read_csv() and unnecessary columns (Caption, Hashtags) were dropped to focus on numeric data relevant to modeling.

3. Feature Selection
The independent variables (X) include Likes, Impressions, Saves, Shares, Profile Visits, etc., while the target variable (y) is Follows.

4. Train-Test Split
The dataset was split into training and testing sets using train_test_split() to evaluate model generalization.

5. Exploratory Data Analysis
A correlation heatmap was plotted to visualize inter-feature relationships and check multicollinearity between predictors.

6. Model Building
Two machine learning models were trained:

Linear Regression: Simple baseline model

Random Forest Regressor: More robust ensemble model

The Random Forest model showed higher accuracy and better handling of nonlinear relationships among features.

7. Model Evaluation
The performance of the Random Forest model was evaluated using the R² score, and a scatter plot of actual vs predicted Follows was generated to visualize prediction accuracy.

# Results
The Random Forest Regressor outperformed the Linear Regression model with a strong R² score, indicating good predictive power.

Visual inspection showed that predicted follower counts closely aligned with actual values, suggesting the model captured key data patterns effectively.

# Conclusion
This project successfully demonstrates how machine learning can be applied to predict Instagram follower growth based on content performance metrics. Using Walmart’s Instagram dataset, insights were generated that can help digital marketers optimize post performance to gain more followers. The workflow can easily be extended to other engagement metrics or brands.
