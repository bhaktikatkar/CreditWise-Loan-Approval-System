# CreditWise Loan Approval System

## 📌 Project Overview

CreditWise Loan Approval System is a machine learning project focused on analyzing loan applicant data and exploring factors associated with loan approval decisions.
The project uses Python for data cleaning, exploratory data analysis (EDA), and data preprocessing as the foundation for developing a loan approval prediction system.

## 🎯 Problem Statement

Manual loan application assessment can be time-consuming and inconsistent. 
This project explores how historical loan applicant data can be analyzed to support data-driven loan approval decisions.
The objective is to prepare applicant data and investigate patterns related to loan approval outcomes.

## 🎯 Project Objectives

- Clean and preprocess the loan applicant dataset.
- Handle missing values in numerical and categorical features.
- Perform exploratory data analysis.
- Visualize applicant demographics and financial attributes.
- Explore relationships between applicant characteristics and loan approval status.
- Prepare the dataset for machine learning model development.

## 📊 Dataset Description

The project uses `loan_approval_data.csv`, provided as part of the Machine Learning and Data Science course by Apna College. 
It contains 1,000 records and 20 columns covering applicant demographics, financial details, credit information, loan attributes, and loan approval status.

  **Key Features**
- Applicant Details: Age, gender, marital status, education, and dependents
- Financial Information: Applicant income, co-applicant income, savings, and collateral value
- Credit Information: Credit score, existing loans, and debt-to-income ratio
- Loan Details: Loan amount, loan term, loan purpose, employment status, and property area
- Target Variable:`Loan_Approved` — indicates whether a loan was approved or rejected
 
- `1` — Approved
- `0` — Rejected

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## ⚙️ Implementation

### 1. Data Loading and Inspection
Loaded the CSV dataset using Pandas and inspected its structure, data types, summary statistics, and missing values.

### 2. Data Cleaning
Used Scikit-learn's `SimpleImputer` to handle missing values:
- Mean imputation for numerical columns.
- Most-frequent-value imputation for categorical columns.

### 3. Exploratory Data Analysis (EDA)
Created visualizations to explore the dataset, including:
- Loan approval distribution using a pie chart.
- Gender and education-level distributions.
- Applicant and co-applicant income distributions.
- Box plots for income, credit score, debt-to-income ratio, and savings.
- Credit score and applicant income distributions grouped by loan approval status.

### 4. Initial Data Preprocessing
Removed `Applicant_ID`, an identifier column, to prepare the dataset for further analysis.

## 📁 Project Files

- `creditwise_loan.ipynb` — Jupyter Notebook containing data cleaning, exploratory analysis, visualizations, and initial preprocessing.
- `loan_approval_data.csv` — Dataset used for analysis.

## 🚧 Project Status

Completed data cleaning, exploratory data analysis (EDA), and initial data preprocessing.
Machine learning model development and evaluation are planned.
Interactive dashboard development is planned.

## 🚀 Future Enhancements

- Implement and evaluate a classification model.
- Measure model performance using appropriate evaluation metrics.
- Develop an interactive dashboard to present key insights.
- Document model results and limitations.

