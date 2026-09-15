# Telecom Customer Churn Prediction (PRCL-0017)

Machine learning classification project to predict customer churn (YES/NO) for a telecom client.

## Project Overview

Built an end-to-end churn prediction pipeline covering data preprocessing, exploratory data analysis, classification model comparison, probability-based risk scoring, and business-oriented evaluation.

## Dataset

The dataset contains customer-level telecom information including:

- Customer demographics
- Telecom partner
- Location information
- Customer tenure
- Usage-related metrics
- Churn outcome

**Target:** `churn` (YES/NO)

## Workflow

1. Data preprocessing and cleaning
2. Exploratory Data Analysis (EDA)
3. Feature preparation
4. Classification model training
5. Model comparison
6. Probability and threshold analysis
7. Churn risk scoring
8. Business recommendation

## Models Compared

- Logistic Regression
- Decision Tree
- Random Forest
- Gradient Boosting

## Results

All evaluated models produced a **ROC-AUC of approximately 0.50**, indicating that the available features provided limited predictive signal for distinguishing churners from non-churners.

Rather than overstating model performance, the project documents this limitation and translates it into a practical business recommendation.

## Business Recommendation

The available dataset should be enriched with additional customer-behavior and business-related features, such as:

- Contract type
- Billing and payment history
- Customer complaints
- Service issues
- Customer support interactions
- Plan changes

These additional features could provide stronger signals for identifying customers at risk of churn.

## Business-Oriented Output

The pipeline generates:

- Churn probability
- Customer risk score
- Risk flag based on prediction threshold

This allows model predictions to be interpreted as actionable customer-risk information.

## Tech Stack

Python · Pandas · NumPy · Scikit-learn · Jupyter Notebook

## Files

- Main notebook — Complete churn classification pipeline
