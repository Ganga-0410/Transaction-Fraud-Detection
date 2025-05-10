# Transaction Fraud Detection

This project aims to detect fraudulent transactions using various machine learning models. The dataset used for this project is synthetic and contains transaction details, user information, and fraud indicators.

## Table of Contents
- Project Overview
- [Dataset](#datasettion
- Usage
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Model Training
- Results
- Contributing
- License

## Project Overview
The goal of this project is to build a model that can accurately detect fraudulent transactions. The project involves data preprocessing, exploratory data analysis, and training multiple machine learning models to achieve the best performance.

## Dataset
The dataset contains 50,000 entries and 21 columns, including:
- `Transaction_ID`
- `User_ID`
- `Transaction_Amount`
- `Transaction_Type`
- `Timestamp`
- `Account_Balance`
- `Device_Type`
- `Location`
- `Merchant_Category`
- `IP_Address_Flag`
- `Previous_Fraudulent_Activity`
- `Daily_Transaction_Count`
- `Avg_Transaction_Amount_7d`
- `Failed_Transaction_Count_7d`
- `Card_Type`
- `Card_Age`
- `Transaction_Distance`
- `Authentication_Method`
- `Risk_Score`
- `Is_Weekend`
- `Fraud_Label`

## Installation
To run this project, you need to have Python installed along with the following libraries:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- xgboost

## Data Preprocessing
- Convert the Timestamp column to datetime format.
- Create a new Date column from the Timestamp.
- Convert specific columns to categorical types.
- Exploratory Data Analysis (EDA)
- Visualize the distribution of transactions across different locations and device types.
- Generate summary statistics for numerical columns.
- Model Training

# The project trains three machine learning models:
- Logistic Regression
- Random Forest Classifier
- XGBoost Classifier
