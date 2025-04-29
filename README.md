# 💼 Bank Customer Churn Prediction

This machine learning project uses real bank customer data to predict customer churn using Logistic Regression, Random Forest, and XGBoost.

## 🔧 Tools Used

- Python
- Pandas
- Scikit-learn
- XGBoost
- Matplotlib, Seaborn

## 📊 Models Compared

- Logistic Regression
- Random Forest Classifier
- XGBoost Classifier

## ✅ Results

| Model              | Accuracy | Recall (Churn) |
|-------------------|----------|----------------|
| Logistic Regression | 81.1%     | 0.20           |
| Random Forest       | 86.9%     | 0.48           |
| XGBoost             | 86.5%     | 0.50           |

## 📈 Visualizations

- ROC Curve Comparison
- XGBoost Feature Importance

## 📌 Key Insights

- Age, Balance, and Activity Level are strong churn indicators.
- XGBoost provided the best balance between precision and recall.

## 📁 Project Files

- `churn_prediction.ipynb` - Full ML code
- `churn_modeling.csv` - Dataset
- `README.md` - Project documentation
