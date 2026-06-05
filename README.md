# 🏦 Loan Approval Prediction using Machine Learning

## 📌 Overview

This project predicts whether a loan application will be **Approved ✅** or **Rejected ❌** using Machine Learning models.

The system analyzes applicant financial and personal details such as:

* 💰 Income
* 🏠 Assets
* 📊 CIBIL Score
* 🎓 Education
* 👨‍💼 Employment Status
* 👨‍👩‍👧 Dependents

The main objective of this project is to demonstrate how Machine Learning can help financial institutions make faster and more accurate loan approval decisions.

---

# 📂 Dataset Information

The dataset contains financial details of loan applicants.

## 📋 Features Used

* 👨‍👩‍👧 Number of Dependents
* 🎓 Education
* 👨‍💼 Self Employed Status
* 💰 Annual Income
* 🏦 Loan Amount
* 📅 Loan Term
* 📊 CIBIL Score
* 🏠 Residential Assets
* 🏢 Commercial Assets
* 💎 Luxury Assets
* 🏛️ Bank Assets

## 🎯 Target Variable

* Loan Status → Approved ✅ / Rejected ❌

---

# ⚙️ Project Workflow

## 1️⃣ Data Understanding

* Explored dataset structure
* Checked data types
* Verified missing values
* Analyzed statistical summaries

---

## 2️⃣ Data Cleaning

* Removed unwanted spaces from column names
* Cleaned categorical values
* Removed unnecessary columns like `loan_id`

---

## 3️⃣ Exploratory Data Analysis (EDA)

Performed analysis to understand relationships between features and loan approval.

## 🔍 Key Insights

* 📊 Higher CIBIL score strongly increases approval chances
* 🎓 Education has very little impact
* 👨‍💼 Self-employment status does not significantly affect approval
* 👨‍👩‍👧 Applicants with fewer dependents have slightly higher approval rates

---

# 📈 Data Visualization

Created multiple visualizations:

* 📊 Count Plots
* 📉 Histograms
* 🔥 Correlation Heatmap
* 📌 Scatter Plots
* ✅ Confusion Matrix

---

# 🛠️ Feature Engineering

## 🔄 Encoding Techniques

* Label Encoding
* One-Hot Encoding

## 📏 Feature Scaling

Used `StandardScaler` for scaling numerical features.

---

# 🤖 Machine Learning Models Used

* Logistic Regression
* Decision Tree
* Random Forest
* XGBoost 🚀

---

# 📊 Model Performance

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | 90.42%   |
| Decision Tree       | 97.60%   |
| Random Forest       | 97.25%   |
| XGBoost 🚀          | 98.20%   |

## 🏆 Best Model

XGBoost achieved the highest accuracy of **98.20%**.

---

# ✅ Confusion Matrix Result

The XGBoost model showed excellent prediction performance with only a very small number of incorrect predictions.

* ✅ Correctly Predicted Rejected Loans: **308**
* ✅ Correctly Predicted Approved Loans: **512**
* ❌ Total Misclassifications: **15**

---

# 💻 Technologies Used

* Python 🐍
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost

---

# 🎯 Conclusion

This project demonstrates how Machine Learning can be used to automate loan approval prediction with high accuracy.

Among all the models tested, **XGBoost 🚀** performed the best with an impressive accuracy of **98.20%**, making it highly effective for loan approval prediction tasks.

---

# 👩‍💻 Author

**Tanu Sharma**
