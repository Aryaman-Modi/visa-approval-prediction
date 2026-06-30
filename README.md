# 🛂 EasyVisa - Visa Approval Prediction using Machine Learning

A Machine Learning classification project that predicts whether a US work visa application will be **Certified** or **Denied** based on applicant and employer information.

This project was developed as part of a business analytics case study to assist the Office of Foreign Labor Certification (OFLC) in making faster and more accurate visa approval decisions.

---

## 📌 Business Problem

The Office of Foreign Labor Certification (OFLC) receives thousands of visa applications every year. Manually reviewing each application is time-consuming and resource-intensive.

The objective of this project is to develop a machine learning model that can:

- Predict whether a visa application will be approved or denied.
- Identify the key factors influencing visa certification.
- Help automate and improve the visa screening process.

---

## 📊 Dataset

The dataset contains **25,480 visa applications** with employee and employer-related information.

### Features include:

- Education Level
- Continent
- Job Experience
- Job Training Requirement
- Company Size
- Year Established
- Region of Employment
- Prevailing Wage
- Wage Unit
- Full-Time Position

**Target Variable**

- Case Status (Certified / Denied)

---

## 📈 Exploratory Data Analysis

The analysis includes:

- Dataset overview
- Missing value analysis
- Univariate analysis
- Bivariate analysis
- Correlation analysis
- Outlier detection
- Feature distributions

---

## ⚙️ Data Preprocessing

- Removed unnecessary columns
- Handled outliers
- Feature engineering
- Converted wage units into yearly wage
- Encoded categorical variables
- Train-Test Split
- Addressed class imbalance using SMOTE

---

## 🤖 Machine Learning Models

The following classification models were evaluated:

- Logistic Regression
- Decision Tree
- Random Forest
- AdaBoost
- Gradient Boosting

---

## 📊 Model Evaluation

Performance was compared using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score
- Confusion Matrix

---

## 📁 Repository Structure

```
easyvisa-visa-approval-prediction
│
├── data
│   └── EasyVisa.csv
│
├── notebooks
│   └── Visa_Approval_Prediction.ipynb
│
├── images
│   └── EDA plots
│
├── reports
│   └── EasyVisa_Business_Report.pdf
│
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore
```

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Imbalanced-Learn (SMOTE)
- Jupyter Notebook

---

## 📌 Key Insights

- Applicants with prior job experience had a higher likelihood of visa approval.
- Full-time positions were approved more frequently than part-time positions.
- Higher prevailing wages showed a positive relationship with certification.
- Education level and region of employment significantly influenced approval rates.

---

## 🚀 Future Improvements

- Hyperparameter optimization using GridSearchCV
- Model deployment with Streamlit
- Explainability using SHAP values
- Interactive dashboard with Tableau or Power BI

---

## 📄 Business Report

A detailed business report containing the complete analysis and recommendations is available in the **reports** folder.

---

## 👨‍💻 Author

**Aryaman Modi**

LinkedIn: *(Add your LinkedIn URL here)*

GitHub: https://github.com/Aryaman-Modi
