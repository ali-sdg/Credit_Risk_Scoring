# Credit Risk Scoring

A machine-learning pipeline to predict **Loan Default** using the `Loans.csv` dataset.

## Workflow
- EDA  
- Preprocessing (Imputation, Encoding, Scaling, SMOTE)  
- Modeling (Logistic Regression, Random Forest, XGBoost)  
- Threshold Tuning for business decisions  

## Dataset
Target: `Loan_Status`
Features: demographics, income, loan amount, credit history, property area.

## Model Performance
**XGBoost** – ROC-AUC: 0.867  
**Random Forest** – ROC-AUC: 0.867  
**Logistic Regression** – ROC-AUC: 0.859  

## Files


01_data_exploration.ipynb
02_preprocessing_feature_engineering.ipynb
03_modeling_and_evaluation.ipynb
04_threshold_and_business_analysis.ipynb


## Future
- Hyperparameter tuning  
- SHAP explainability  
- Deployment (FastAPI/Streamlit)
