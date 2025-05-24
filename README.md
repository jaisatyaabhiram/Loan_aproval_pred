# 🏦 Loan Approval Classifier

A Machine Learning project to predict whether a loan application should be **approved or rejected** based on the applicant’s profile data.

This project is part of **"7 Days of AI: Build Real Projects with Me!"** – **Day 2: Classification**.

---

## ✅ Project Objective

To build a binary classification model that automates the loan approval process using applicant information like income, credit history, education, and more.

---

## 📋 Dataset Features Used

| Feature              | Description                                |
|----------------------|--------------------------------------------|
| `Gender`             | Male / Female                              |
| `Married`            | Marital status (Yes / No)                  |
| `Dependents`         | Number of dependents (0, 1, 2, 3+)         |
| `Education`          | Education level (Graduate / Not Graduate)  |
| `Self_Employed`      | Employment status (Yes / No)               |
| `ApplicantIncome`    | Applicant monthly income                   |
| `CoapplicantIncome`  | Co-applicant monthly income                |
| `LoanAmount`         | Requested loan amount                      |
| `Loan_Amount_Term`   | Duration of the loan (in months)           |
| `Credit_History`     | 1 = Good credit, 0 = Poor credit           |
| `Property_Area`      | Urban, Semiurban, Rural                    |

🎯 **Target Variable**:  
- `Loan_Status` – 1 = Approved, 0 = Rejected

---

## 🔍 Algorithms Applied

- **Logistic Regression**
- **K-Nearest Neighbors (KNN)**
- **Support Vector Machine (SVM)**
- **Random Forest Classifier**

---

## 🧪 Evaluation Metrics

- Accuracy
- Confusion Matrix
- Precision
- Recall
- F1-score
- Decision Boundaries (Visualized in 2D)

---

## 🛠️ Tech Stack

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook / Google Colab

---

## 🧹 Preprocessing Steps

- Converted categorical variables using label encoding and one-hot encoding
- Scaled numeric features using StandardScaler
- Filled missing values with median strategy
- Replaced '3+' in `Dependents` with numeric 3

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/loan-approval-classifier.git
   cd loan-approval-classifier
