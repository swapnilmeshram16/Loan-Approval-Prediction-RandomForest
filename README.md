# Loan-Approval-Prediction-RandomForest
This machine learning project predicts whether a loan will be approved based on user inputs using a Random Forest Classifier. It performs data preprocessing, label encoding, scaling, model training, and user input prediction.

---

## 🔍 Features

- Predicts loan approval status (Approved/Rejected)
- Takes 15-step user input from real-time user
- Uses Label Encoding + Standard Scaler
- Random Forest Classifier
- Accuracy: ~77%
- Easily extendable with other ML models like XGBoost, CatBoost

---

## 📂 Files Included

- `loan_approval_model.ipynb`: Main notebook (training + prediction)
- `train_u6lujuX_CVtuZ9i.csv`: Training dataset
- `test.csv`: Testing dataset
- `README.md`: Project details and usage guide

---

## 🧠 ML Workflow

1. Data Cleaning
2. Missing Value Handling
3. Label Encoding (for categorical features)
4. Feature Scaling
5. Train-Test Split
6. Model Training (RandomForestClassifier)
7. Accuracy Evaluation
8. User Input Form (15-step)
9. Final Prediction (Approved / Rejected)

---

## 📈 Model Performance

- Accuracy: **~77%**
- F1 Score: Good on both approved (1) and rejected (0) classes
- Can be improved using SMOTE / Hyperparameter Tuning / Ensemble methods

