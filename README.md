# Paisabazaar Banking Fraud Analysis

## Project Overview

The **Paisabazaar Banking Fraud Analysis** project is designed to analyze a large dataset of banking customers to identify potential fraudulent activities. The dataset includes detailed information about customers' financial behaviors, credit histories, and transaction details. The goal of this project is to detect anomalies and patterns that may indicate fraudulent behavior, such as credit card fraud, loan exploitation, or unusual financial transactions.

## Problem Statement

Given a dataset of 100,000 banking customers with comprehensive financial and personal information, this project aims to analyze the data to detect and flag potential fraudulent activities. The analysis will focus on identifying deviations from typical customer behavior and assessing risk indicators to improve fraud detection mechanisms.

## Dataset

The dataset contains the following columns:

- `ID`: Unique identifier for each record
- `Customer_ID`: Unique identifier for each customer
- `Month`: Time period of the data
- `Name`: Name of the customer
- `Age`: Age of the customer
- `SSN`: Social Security Number
- `Occupation`: Occupation of the customer
- `Annual_Income`: Annual income of the customer
- `Monthly_Inhand_Salary`: Monthly salary of the customer
- `Num_Bank_Accounts`: Number of bank accounts held
- `Num_Credit_Card`: Number of credit cards held
- `Interest_Rate`: Interest rate on loans
- `Num_of_Loan`: Number of loans taken
- `Type_of_Loan`: Type of loan
- `Delay_from_due_date`: Delay in payment from the due date
- `Num_of_Delayed_Payment`: Number of delayed payments
- `Changed_Credit_Limit`: Changes in credit limit
- `Num_Credit_Inquiries`: Number of credit inquiries
- `Credit_Mix`: Credit mix
- `Outstanding_Debt`: Outstanding debt amount
- `Credit_Utilization_Ratio`: Ratio of credit utilization
- `Credit_History_Age`: Age of credit history
- `Payment_of_Min_Amount`: Minimum payment status
- `Total_EMI_per_month`: Total EMI payment per month
- `Amount_invested_monthly`: Amount invested monthly
- `Payment_Behaviour`: Payment behavior
- `Monthly_Balance`: Monthly balance
- `Credit_Score`: Credit score

## Methodology

1. **Data Wrangling**: Clean and preprocess the data by handling missing values, encoding categorical variables, and normalizing numerical features.
2. **Exploratory Data Analysis (EDA)**: Conduct initial analysis to understand data distributions, detect outliers, and identify patterns.
3. **Feature Engineering**: Create new features and metrics that could be useful for detecting fraudulent behavior.
4. **Visualization**: Utilize various visualization techniques to analyze and interpret data patterns and anomalies.
5. **Fraud Detection**: Apply statistical methods and machine learning models to identify potential fraud based on the analyzed data.

## Installation

To run this project, you need to have Python and the required libraries installed. You can install the necessary libraries using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn

## Link of the explanation video:-
https://youtu.be/0x4X3xLO-MU?si=Q4VUywkKEhXCSL1I
