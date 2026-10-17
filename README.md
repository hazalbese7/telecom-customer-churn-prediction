# Telecom Customer Churn Analysis & Prediction

An ongoing data science project exploring customer churn patterns in the IBM Telco Customer Churn dataset, with a focus on exploratory data analysis and future machine learning applications.

## Project Overview

This project aims to investigate factors associated with customer churn in the telecommunications industry and build a foundation for predictive modeling.

**Dataset:** IBM Telco Customer Churn — 7,043 customer records.

## Technologies

- Python
- Pandas and NumPy
- Matplotlib
- Google Colab

## Exploratory Data Analysis

The analysis focuses on three main areas:

**1. Contract Type**

- Month-to-month contracts: 42.7% churn
- Two-year contracts: 2.8% churn

**2. Monthly Charges**

- Customers who churned: 74.44 average monthly charges
- Customers who stayed: 61.27 average monthly charges

**3. Customer Tenure**

Observed churn rates decreased across longer-tenure groups, from 47.43% among customers with 0–12 months of tenure to 9.51% among those with 49–72 months.

These are descriptive associations and do not establish causal relationships.

## Data Preparation

- Inspected dataset structure and data types.
- Identified 11 missing values in `TotalCharges`.
- Converted `TotalCharges` to numeric.
- Imputed missing values as zero for customers with zero tenure, under a documented assumption.

## Project Status

**Completed:** Initial exploratory data analysis and visualizations.

**Next steps:** Feature preprocessing, model training, evaluation and interpretation.

## Dataset Attribution

IBM Telco Customer Churn dataset, publicly available for educational analysis.

*This is an independent educational project and is not affiliated with Vodafone.*
