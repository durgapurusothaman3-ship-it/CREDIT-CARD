                                   Credit Card Fraud Detection System
Project Overview

The Credit Card Fraud Detection System is a data analytics and machine learning project developed using the Kaggle Credit Card Fraud Dataset.
The project focuses on identifying fraudulent transaction patterns using:

Exploratory Data Analysis (EDA)
Data Visualization
Risk Analysis
Linear Regression Modeling
Interactive Dashboard Creation

The system helps financial institutions analyze transaction behavior and improve fraud monitoring strategies.

Problem Statement

Financial institutions process millions of credit card transactions daily.
Among these transactions, some are fraudulent and unauthorized, leading to:

Financial losses
Unauthorized access
Poor fraud risk management
Reduced customer trust

Manual fraud detection is inefficient due to the massive volume of transactions.
This project aims to automate fraud analysis and support fraud detection through data analytics and machine learning techniques.

Dataset Information
Dataset Name: Credit Card Fraud Detection Dataset
Dataset Source: Kaggle

Kaggle Credit Card Fraud Dataset

Dataset Features
Column	Description
Time	Time elapsed between transactions
Amount	Transaction amount
V1 – V28	Anonymized transaction features
Class	Target variable (0 = Normal, 1 = Fraud)
Project Objectives

The project aims to:

Load and understand transaction data
Perform data cleaning and preprocessing
Analyze fraud vs normal transaction behavior
Perform descriptive statistical analysis
Identify suspicious transaction patterns
Build a Linear Regression model
Evaluate model performance
Create interactive dashboards using Plotly
Generate insights for fraud prevention
Technologies Used
Programming Language
Python
Libraries Used
pandas
numpy
matplotlib
seaborn
plotly
scikit-learn
Project Workflow
1. Data Collection
Load dataset from Kaggle
Explore dataset structure
2. Data Cleaning
Handle missing values
Remove duplicate records
Verify data types
3. Exploratory Data Analysis (EDA)
Fraud distribution analysis
Transaction amount analysis
Time-based analysis
Correlation analysis
4. Data Visualization
Bar charts
Histograms
Scatter plots
Box plots
Heatmaps
5. Risk Analysis

Transactions are categorized into:

Low Risk
Medium Risk
High Risk
6. Predictive Modeling

Linear Regression is used for:

Transaction trend prediction
Fraud-related behavior analysis
7. Model Evaluation

Performance metrics:

R² Score
Mean Absolute Error (MAE)
Mean Squared Error (MSE)
8. Dashboard Creation

Interactive dashboards are built using Plotly.

Project Structure
Credit-Card-Fraud-Detection/
│
├── creditcard.csv
├── fraud_detection.py
├── cleaned_creditcard.csv
├── README.md
└── requirements.txt
