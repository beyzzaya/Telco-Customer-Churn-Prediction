# Telco-Customer-Churn-Prediction
This repository hosts **`Telco-Customer-Churn-Prediction.ipynb`**, a hands-on notebook that predicts
whether a Telco customer will churn.  
Key steps:

- Loads the public **Telco-Customer-Churn** dataset  
  (`Telco-Customer-Churn.csv`).
- Cleans data (e.g., converts *TotalCharges* to numeric, drops blanks).
- Uses **SMOTE** to balance the classes.
- Compares five models  
  (Logistic Regression, KNN, Decision Tree, Random Forest, Gradient Boosting).
- **Best baseline:** Logistic Regression → *Accuracy* **0.79**, *ROC AUC* **0.856**.  
- Performs **GridSearchCV** on Random Forest  
  → cross-val *ROC AUC* **0.92**, test *ROC AUC* **0.834**, *Accuracy* **0.78**.
