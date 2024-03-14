# Industrial Copper Modeling

Enhance your proficiency in data analysis and machine learning with our "Industrial Copper Modeling" project. In the copper industry, dealing with complex sales and pricing data can be challenging. Our solution employs advanced machine learning techniques to address these challenges, offering regression models for precise pricing predictions and lead classification for better customer targeting. You'll also gain experience in data preprocessing, feature engineering, and web application development using Streamlit, equipping you to solve real-world problems in manufacturing.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

Enhance your proficiency in data analysis and machine learning with our "Industrial Copper Modeling" project. In the copper industry, dealing with complex sales and pricing data can be challenging. Our solution employs advanced machine learning techniques to address these challenges, offering regression models for precise pricing predictions and lead classification for better customer targeting. You'll also gain experience in data preprocessing, feature engineering, and web application development using Streamlit, equipping you to solve real-world problems in manufacturing.

## Features

### Data Preprocessing

- **Data Understanding:** Identify types of variables, distinguish between continuous and categorical variables, and examine their distributions.
- **Handling Null Values:** Address missing values through appropriate imputation methods.
- **Encoding and Data Type Conversion:** Prepare categorical features for modeling and ensure data types match modeling requirements.
- **Skewness - Feature Scaling:** Identify and mitigate skewness in continuous variables through appropriate transformations.
- **Outliers Handling:** Address outliers using the Interquartile Range (IQR) method.
- **Wrong Date Handling:** Correct delivery dates to maintain data integrity.

### Exploratory Data Analysis (EDA) and Feature Engineering

- **Skewness Visualization:** Visualize and correct skewness in continuous variables.
- **Outlier Visualization:** Identify and rectify outliers.
- **Feature Improvement:** Create new features to gain deeper insights from the data.

### Classification

- **Success and Failure Classification:** Utilize the 'status' variable to classify successes and failures.
- **Handling Data Imbalance:** Address data imbalance using the SMOTETomek oversampling method.
- **Algorithm Assessment:** Assess performance of various algorithms for classification.
- **Algorithm Selection:** Choose the Random Forest Classifier for robust performance.
- **Hyperparameter Tuning:** Fine-tune the model using GridSearchCV and cross-validation.
- **Model Accuracy and Metrics:** Evaluate model performance using key metrics.
- **Model Persistence:** Save the trained model for future use.

### Regression

- **Algorithm Assessment:** Assess performance of various algorithms for regression.
- **Algorithm Selection:** Choose the Random Forest Regressor for robust performance.
- **Hyperparameter Tuning:** Fine-tune the model using GridSearchCV and cross-validation.
- **Model Accuracy and Metrics:** Evaluate model performance using key metrics.
- **Model Persistence:** Save the trained model for future use.

## Installation

To run this project, you need to install the following packages:

pip install numpy
pip install pandas
pip install scikit-learn
pip install xgboost
pip install matplotlib
pip install seaborn
pip install streamlit

## Usage

To use this project, follow these steps:

1. Install the required packages: `pip install -r requirements.txt`
2. Run the Streamlit app: `streamlit run app.py`
3. Access the app in your browser at [http://localhost:8501](http://localhost:8501)
