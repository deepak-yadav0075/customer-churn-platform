# Customer Churn Prediction Platform

An end-to-end Machine Learning web application that predicts customer churn risk using customer behavior, service usage, contract details, and payment information. The project includes data preprocessing, exploratory data analysis, model training, evaluation, explainability, and deployment using Streamlit.

## Live Demo

[Open Streamlit App](https://customer-churn-platform-app.streamlit.app/)

## Project Overview

Customer churn is a major business problem where companies lose existing customers. This project helps identify customers who are likely to leave so that businesses can take early action through retention strategies.

The platform predicts whether a customer is likely to churn and provides churn probability, risk level, and business recommendations.

## Key Features

* Customer churn prediction using Machine Learning
* Interactive Streamlit dashboard
* Single customer prediction
* Batch CSV prediction
* Churn probability and risk segmentation
* Exploratory Data Analysis
* Feature importance analysis
* SHAP-based explainability
* Business recommendations for customer retention

## Tech Stack

* Python
* Pandas
* NumPy
* Scikit-Learn
* Random Forest Classifier
* SHAP
* Matplotlib
* Seaborn
* Streamlit
* Pickle

## Machine Learning Workflow

1. Data loading
2. Data cleaning
3. Handling missing values
4. Encoding categorical features
5. Feature scaling
6. Train-test split
7. Model training
8. Model evaluation
9. Model saving
10. Streamlit deployment

## Model Performance

* Accuracy: 80.55%
* F1 Score: 0.8002
* Model Used: Random Forest Classifier

## Dataset

The project uses the Telco Customer Churn dataset with customer demographic, account, service, and billing information.

Dataset shape:

```text
Rows: 7,043
Columns: 21
```

## Project Structure

```text
customer-churn-platform/
│
├── dashboard/
│   ├── app.py
│   └── pages/
│
├── data/
│   └── raw/
│
├── models/
│   ├── random_forest.pkl
│   ├── scaler.pkl
│   └── model_columns.pkl
│
├── notebooks/
│
├── src/
│
├── assets/
│
├── requirements.txt
├── README.md
└── .gitignore
```

## How to Run Locally

Clone the repository:

```bash
git clone https://github.com/vickycodeswith/customer-churn-platform.git
cd customer-churn-platform
```

Create a virtual environment:

```bash
python -m venv venv
```

Activate the virtual environment:

For Windows:

```bash
venv\Scripts\activate
```

For macOS/Linux:

```bash
source venv/bin/activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the Streamlit app:

```bash
streamlit run dashboard/app.py
```

## Business Use Case

This project can help telecom companies:

* Identify high-risk churn customers
* Understand important churn factors
* Improve customer retention strategy
* Reduce revenue loss
* Support data-driven decision making

## Author

**Nitesh Kumar Yadav**
B.Tech Computer Engineering
Data Analyst | Python | SQL | Machine Learning | Streamlit
