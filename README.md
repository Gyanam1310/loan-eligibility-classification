# Loan Approval Prediction using Machine Learning

This project predicts whether a loan application will be approved using machine learning models.

---

## 📌 Problem Statement

Given applicant details such as income, education, dependents, etc., the goal is to predict loan approval status.

---

## 🛠️ Workflow

The following steps were performed:

- Data Cleaning
- Handling Missing Values
- Feature Engineering
- Log Transformations
- Exploratory Data Analysis (EDA)
- Model Training
- Hyperparameter Tuning

---

## 🤖 Models Used

- Decision Tree
- Support Vector Machine (SVM)
- Tuned SVM using GridSearchCV

---

## 📊 Results

| Model            | Train Accuracy | Test Accuracy |
|------------------|---------------|--------------|
| Decision Tree    | 0.8167        | 0.7480       |
| Base SVM         | 0.7882        | 0.7724       |
| Tuned SVM        | -             | **0.7886**   |

---

## 🏆 Best Model

Tuned **SVM (Linear Kernel, C = 0.1)** gave the best performance and generalization.

---

## 🚀 Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## ✅ Conclusion

Hyperparameter tuning improved model performance, and the tuned SVM was selected as the final model.

---
