# Loan Risk Prediction using Ensemble Learning

This project predicts the likelihood of loan default using ensemble learning techniques on a dataset of over 200k records.

## Models Used
- Random Forest (Bagging)
- XGBoost (Boosting)

## Approach
- Selected relevant features and removed missing values  
- Encoded categorical variables using one-hot encoding  
- Trained both models with comparable configurations for fair analysis  
- Evaluated performance using accuracy and log loss  

## Results
- Both Random Forest (bagging) and XGBoost (boosting) achieved similar accuracy (~86.5%)  
- Log loss analysis showed differences in convergence behavior between the two methods  
- Boosting demonstrated more stable and faster convergence compared to bagging 

## Tech Stack
- Python  
- scikit-learn  
- XGBoost  

## File
- loan_risk_ensemble.ipynb contains preprocessing, training, and evaluation
