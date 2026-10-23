# Telecom Customer Churn Analysis & Prediction

An end-to-end introductory data science project exploring customer churn and developing a machine learning model using the IBM Telco Customer Churn dataset.

## Project Overview

The objective of this project is to analyze customer churn patterns and predict whether a telecommunications customer is likely to leave.

The project includes exploratory data analysis, data preprocessing, classification modeling, feature comparison, threshold analysis, and model evaluation.

**Dataset:** IBM Telco Customer Churn — 7,043 customer records.

## Technologies

- Python
- Pandas and NumPy
- Matplotlib
- Scikit-learn
- Google Colab

## Project Notebooks

**01 — Exploratory Data Analysis**

Explores relationships between churn and contract type, monthly charges, and customer tenure. Includes data quality checks and visualizations.

**02 — Churn Prediction Model**

Builds and evaluates Logistic Regression models using three and eight customer features. Compares classification thresholds using validation data and evaluates the selected model on the test set.

## Key Findings

- Month-to-month contracts had a churn rate of approximately 42.7%, compared with 2.8% for two-year contracts.
- Customers who churned had higher average monthly charges than customers who stayed.
- Customers with shorter observed tenure had higher churn rates.
- Expanding the model from three to eight features produced modest validation improvements.
- Lowering the classification threshold from 0.50 to 0.40 improved validation recall, with a trade-off in precision.

## Final Model Performance

Eight-feature Logistic Regression with a classification threshold of 0.40.

| Metric | Test Result |
|---|---:|
| Accuracy | 77.22% |
| Precision | 56.21% |
| Recall | 64.17% |
| F1-score | 59.93% |

**Final confusion matrix:**

- True Negatives: 848
- False Positives: 187
- False Negatives: 134
- True Positives: 240

The final model identified 240 of 374 customers who churned.

## Limitations and Future Work

This project uses a public educational dataset, which may not reflect current real-world customer behavior. An initial baseline was evaluated on the test set before the validation workflow was introduced, so the test set was not completely untouched during development.

Future improvements could include cross-validation, additional classification algorithms, probability calibration, and business cost-based threshold selection.

## Author

Hazal Beşe

*Independent educational project. Not affiliated with Vodafone.*
