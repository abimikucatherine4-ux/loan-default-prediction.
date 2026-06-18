# 💳 Loan Default Prediction System
## 📌 Project Overview
This project uses Machine Learning to predict whether a customer is likely to default on a loan based on their financial and personal information. The goal is to help financial institutions identify high-risk borrowers and make informed lending decisions.
## 📊 Dataset
The dataset contains customer loan records with features such as:
* Age
* Income
* Loan Amount
* Credit Score
* Interest Rate
* Loan Term
* Debt-to-Income Ratio (DTI)
* Employment Status
* Education Level
* Marital Status
* Loan Purpose
* Co-signer Information
**Target Variable**
* `Default = 1` → Customer defaults on the loan
* `Default = 0` → Customer repays the loan
## 🧹 Data Processing
The data was cleaned and explored to understand customer behavior and default patterns.
Key preprocessing steps included:
* Missing value checks
* Exploratory Data Analysis (EDA)
* Correlation analysis
* One-hot encoding of categorical features
* Train-test split for model training and evaluation
## 🤖 Model Building & Evaluation
Several machine learning techniques were applied to classify loan defaults, including:
* Logistic Regression
* Random Forest Classifier
* XGBoost Classifier
Model performance was evaluated using:
* Accuracy Score
* F1 Score
* Cross Validation
Feature importance analysis was also performed to identify the factors that most influence loan default risk.

## 🌐 Streamlit Application

A user-friendly Streamlit web application was developed to allow users to:
* Enter customer information
* Generate instant loan default predictions
* View prediction results in real time
* Interact with a simple and intuitive dashboard

## 🚀 How to Run Locally
### Clone the Repository
```bash
git clone https://github.com/your-username/loan-default-prediction.git
cd loan-default-prediction
```

### Install Dependencies
```bash
pip install -r requirements.txt
```
### Run the Streamlit App
```bash
streamlit run app.py
```
The application will open automatically in your browser at:
```text
http://localhost:8501
```
## 📦 Requirements
* Python 3.9+
* Streamlit
* Pandas
* NumPy
* Scikit-learn
* XGBoost
* Matplotlib
* Seaborn
* Pickle## 🎯 Project Goal
To demonstrate how machine learning can be used to assess loan risk, reduce financial losses, and support data-driven lending decisions.
