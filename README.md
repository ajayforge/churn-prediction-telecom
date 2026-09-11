# Telecom Customer Churn Prediction (PRCL-0017)

Classification project to predict customer churn (YES/NO) for a telecom client.

## Dataset
- telecom_churn_data — customer_id, telecom_partner, gender, age, state, city, pincode, tenure, usage metrics, churn

## Approach
- Data preprocessing and exploratory data analysis
- Compared 4 classification models: Logistic Regression, Decision Tree, Random Forest, Gradient Boosting
- Threshold tuning and business-oriented output (churn probability, risk score, flag)

## Results
- All models converged to ROC-AUC ≈ 0.50 — no strong predictive signal in available features
- Documented as an honest finding with recommendation to collect richer data (contract type, billing, complaints)

## Tech Stack
Python, Pandas, NumPy, Scikit-learn, Jupyter Notebook

## Files
- Main notebook — churn classification pipeline
