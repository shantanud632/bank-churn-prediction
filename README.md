# 📈 Customer Churn Prediction - Machine Learning Project

This project builds and evaluates machine learning models to predict customer churn in a bank dataset.  
We compare the performance of Logistic Regression, Random Forest, and XGBoost models using 5-Fold Cross-Validation.

---

## 📂 Project Files

- `churn_prediction.ipynb` — Full Jupyter Notebook including:
  - Data loading and cleaning
  - Feature encoding
  - Cross-validation based model comparison
  - ROC curve comparison for all models
  - Feature importance analysis using XGBoost
  - Final project conclusion
- `Bank Churn Modelling.csv` — Input dataset (optional, if needed separately)

---

## 🧠 Techniques Used

- Data Preprocessing
- Label Encoding
- Feature Scaling (StandardScaler for Logistic Regression)
- 5-Fold Cross-Validation
- ROC Curve and AUC Analysis
- Feature Importance (XGBoost)
- Model Comparison: Logistic Regression, Random Forest, XGBoost

---

## 📊 Key Results

- **Random Forest** and **XGBoost** models achieved an average cross-validation accuracy of ~85%-86%.
- **Feature Importance** showed that **Age**, **Estimated Salary**, and **Credit Score** were the top predictors for churn.
- **ROC Curve Analysis** highlighted that XGBoost delivered a strong AUC score.

---

## 🚀 Tools and Libraries

- Python
- Jupyter Notebook
- Pandas
- Scikit-learn
- XGBoost
- Matplotlib
