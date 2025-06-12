# Telecom-Churn-Analysis
## 📌 Project Description

This project aims to predict customer churn in a telecom company using machine learning techniques. The model helps identify customers who are likely to leave the service so that proactive retention strategies can be implemented.

The dataset includes various features such as tenure, monthly charges, contract type, and services subscribed. The project includes data preprocessing, exploratory data analysis, model training, and evaluation using classification metrics.

## 🧑‍💻 Who Are the End Users?

-Company Executives
-Marketing Teams
-Customer Service Managers
-Data Analysts & Business Intelligence Teams
-Product Development Teams
-Loyalty & CRM Teams


## 💡 Problem Statement

The objective of this project is to develop a machine learning model that predicts customer churn for a telecom company. By analyzing customer data—such as monthly charges, contract type, internet usage patterns, and tenure with the company—the model identifies customers who are at high risk of leaving. This enables the company to proactively engage with these customers through targeted retention strategies like personalized offers or enhanced support, ultimately reducing churn rates and minimizing revenue loss. 

## 🛠️ Technologies Used

- **Language**: Python
- **Tools**: google colab
- **Libraries**: pandas, numpy, matplotlib, seaborn, scikit-learn

## 📊 Results

- The best performing model: Random Forest Classifier
- Key metrics (example):
  - Accuracy: ~82%
  - Precision: ~78%
  - Recall: ~77%
  - F1 Score: ~77%
- Insights:
  - Customers with higher monthly charges are more likely to churn.
  - Longer tenure reduces the likelihood of churn.
  - Fiber optic internet users and customers without tech support are more likely to leave.

## 🗃️ Files in This Repository

- Telecom_Churn_Case_Study.ipynb: The main google colab Notebook with code and visualizations.
- telecom_churn.csv: The dataset used.
- README.md: This file.

## 🚀 How to Run in Google Colab

You can run this project entirely in the cloud using **Google Colab** with no need for local setup. Follow these steps:

### 1. Open the Notebook in Google Colab

Click the badge below to launch the notebook in Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yourusername/telecom-churn-prediction/blob/main/Telecom_Churn_Case_Study.ipynb)

> 📌 Replace `yourusername` with your actual GitHub username in the link above if you haven't yet.

---

### 2. Upload the Dataset

Since Google Colab cannot access files from your computer directly unless uploaded, follow these steps:

1. Click the **folder icon** (📁) in the left sidebar of Colab.
2. Click the **upload icon** (📤).
3. Upload the file named `telecom chrn.csv`.

> ⚠️ Make sure the uploaded file name exactly matches what is referenced in the notebook.

---

### 3. Run All Notebook Cells

- Go through each cell in `Telecom_Churn_Case_Study.ipynb`.
- The notebook includes:
  - Data loading and cleaning
  - Exploratory Data Analysis (EDA)
  - Model training and testing
  - Evaluation metrics (accuracy, precision, recall, F1 score)
  - Business insights

---

### ✅ Output

At the end of execution, you will get:
- A trained churn prediction model
- Visual insights about customer behavior
- Actionable understanding of why customers churn

> ✅ Colab is a free platform that supports GPU acceleration (optional) and requires only a Google account.

