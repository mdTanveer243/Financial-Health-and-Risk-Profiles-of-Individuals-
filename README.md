# Predicting Financial Health and Risk Profiles of Individuals

## Overview
This dataset is designed to help in predicting the **financial health** and **risk profiles** of individuals based on various demographic, financial, and life event variables. The goal is to classify individuals into one of the following categories:
- **Healthy**: An individual with a stable financial situation.
- **Moderate Risk**: An individual with some financial stress or instability.
- **High Risk**: An individual at risk of financial collapse or bankruptcy in the near future.

The dataset contains many features and 100,000 rows of synthetic data. The variables cover various aspects of an individual’s personal, financial, and economic situation, and they can be used to train machine learning models to predict an individual’s financial health.

## Dataset Description

### 1. Demographic Information
- **Age**: Age of the individual (integer, between 18 and 80).
- **Gender**: Gender of the individual (encoded as 0 = Male, 1 = Female).
- **Marital Status**: Marital status of the individual (encoded as 0 = Single, 1 = Married, 2 = Divorced).
- **Number of Dependents**: Number of dependents the individual is financially supporting.
- **Household Size**: Total number of people living in the household, including the individual and dependents.
- **Education Level**: Highest level of education attained (encoded as 0 = High School, 1 = Undergraduate, 2 = Graduate).
- **Occupation**: Occupation of the individual (encoded as 0 = Engineer, 1 = Teacher, 2 = Artist, 3 = Doctor, 4 = Salesperson).
- **Years in Current Job**: Number of years the individual has worked in their current job.
- **Income Level**: Income level of the individual (encoded as 0 = Low, 1 = Medium, 2 = High).
- **Credit Score**: The individual’s credit score (integer, between 300 and 850).
- **Number of Credit Inquiries**: Number of recent credit inquiries made by the individual.
- **Housing Status**: Whether the individual owns or rents their home (encoded as 0 = Owner, 1 = Rent).
- **City or Region of Residence**: Location of residence (encoded as 0 = Urban, 1 = Suburban, 2 = Rural).
- **Previous Bankruptcy Status**: Whether the individual has declared bankruptcy in the past (encoded as 0 = No, 1 = Yes).
- **Health Condition**: The individual’s health condition (encoded as 0 = Good, 1 = Chronic, 2 = Temporary).
- **Family Health History**: Health history in the family (encoded as 0 = None, 1 = Heart Disease, 2 = Cancer).
- **Marital History**: Number of marriages/divorces the individual has experienced.
- **Residency Stability**: Whether the individual has lived in the same location for a significant period (encoded as 0 = Stable, 1 = Unstable).
- **Financial Stability of Parents**: The financial stability of the individual’s parents (encoded as 0 = Stable, 1 = Unstable).

### 2. Financial Behaviors
- **Average Monthly Expenses**: The individual’s average monthly expenses across different categories (integer, between 500 and 5000).
- **Credit Card Usage**: Amount of credit card debt currently owed (integer, between 0 and 5000).
- **Savings Rate**: Percentage of the individual’s income that is saved every month (float between 0 and 1).
- **Number of Loans Taken**: The total number of loans (personal, home, auto, education) the individual has taken.
- **Mortgage Information**: The remaining balance on the individual’s mortgage (integer, between 0 and 500000).
- **Investment Accounts**: The total amount the individual has invested in stocks, bonds, and mutual funds (integer, between 0 and 100000).
- **Emergency Fund Status**: Amount of money the individual has saved for emergencies (integer, between 0 and 20000).
- **Loan Delinquencies History**: The number of past loan delinquencies.
- **Bank Account Activity**: Number of transactions in the individual’s bank account per month.
- **Tax Filing History**: Whether the individual has filed their taxes in the past (encoded as 0 = Not Filed, 1 = Filed).
- **Utility Bills Payment History**: Whether the individual has consistently paid their utility bills on time (encoded as 0 = Late, 1 = Paid).
- **Number of Credit Cards Held**: Total number of credit cards the individual holds.

### 3. Life Events and Personal History
- **Job Loss**: Whether the individual has experienced a job loss in the past (encoded as 0 = No, 1 = Yes).
- **Divorce History**: Whether the individual has been through a divorce (encoded as 0 = No, 1 = Yes).
- **Major Medical Emergency**: Whether the individual has experienced a major medical emergency (encoded as 0 = No, 1 = Yes).
- **Adoption History**: Whether the individual has adopted a child (encoded as 0 = No, 1 = Yes).
- **Bankruptcy History**: Whether the individual has filed for bankruptcy in the past (encoded as 0 = No, 1 = Yes).
- **Health-related Legal Claims**: Whether the individual has had legal claims related to their health (encoded as 0 = No, 1 = Yes).
- **Domestic or International Relocation**: Whether the individual has relocated (domestic or international) in the past (encoded as 0 = No, 1 = Yes).

### 4. External Economic and Market Data
- **Local Unemployment Rate**: The unemployment rate in the individual's local area (float, between 0 and 10).
- **Inflation Rate**: The current inflation rate in the individual's country (float, between 0 and 5).
- **Interest Rates**: Current interest rates (float, between 0 and 7).
- **Economic Sentiment**: The overall economic sentiment (encoded as 0 = Positive, 1 = Neutral, 2 = Negative).

### 5. Financial Planning and Risk Indicators
- **Risk Tolerance**: The individual’s risk tolerance when it comes to investments (integer between 1 and 10, where 1 is low tolerance and 10 is high tolerance).
- **Financial Planner Involvement**: Whether the individual works with a financial planner (encoded as 0 = No, 1 = Yes).
- **Debt-to-Income Ratio**: Ratio of the individual’s total debt to their total income (float between 0 and 1).
- **Life Insurance Adequacy**: Whether the individual’s life insurance coverage is adequate (encoded as 0 = Inadequate, 1 = Adequate).
- **Long-term Financial Goals**: The individual’s long-term financial goals (encoded as 0 = Retirement, 1 = Home Purchase, 2 = Investment).

### 6. Target Variable
- **Risk Profile**: The financial health status of the individual (encoded as 0 = Healthy, 1 = Moderate Risk, 2 = High Risk).

## Task

- **Objective**: Train a machine learning model to predict the financial risk profile of individuals. Provide model explainability to understand the top features affecting financial health.
- **Target Variable**: `Risk Profile` (categorical: `Healthy`, `Moderate Risk`, `High Risk`).
- **Features**: Features covering demographics, financial behaviors, life events, and external economic data.


