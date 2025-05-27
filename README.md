# Loan Approval Prediction Project

This repository contains a Jupyter Notebook for a machine learning project focused on predicting loan approval status based on applicant and asset data. The project demonstrates the complete pipeline from data exploration and preprocessing to model training and evaluation.

---

## **Project Overview**

The objective of this project is to build and evaluate machine learning models that predict whether a loan application will be *Approved* or *Rejected* using various applicant and asset features. The dataset consists of 4,269 records, each with 13 features including demographic, financial, and asset information, along with the loan approval status as the target variable.

---

## **Dataset Description**

The dataset includes the following columns:

| Column Name              | Description                                    |
|--------------------------|------------------------------------------------|
| loan_id                  | Unique identifier for each loan application    |
| no_of_dependents         | Number of dependents of the applicant          |
| education                | Education status (Graduate/Not Graduate)       |
| self_employed            | Whether the applicant is self-employed (Yes/No)|
| income_annum             | Annual income of the applicant                 |
| loan_amount              | Requested loan amount                          |
| loan_term                | Duration of the loan (in months)               |
| cibil_score              | CIBIL credit score of the applicant            |
| residential_assets_value | Value of residential assets                    |
| commercial_assets_value  | Value of commercial assets                     |
| luxury_assets_value      | Value of luxury assets                         |
| bank_asset_value         | Value of bank assets                           |
| loan_status              | Target variable (Approved/Rejected)            |

---

## **Project Structure**

- **Data Exploration:**  
  - Summary statistics, missing value analysis, and data visualization.
- **Data Preprocessing:**  
  - Handling missing values.
  - Encoding categorical variables (e.g., education, self_employed).
  - Feature scaling/normalization.
- **Model Building:**  
  - Logistic Regression and K-Nearest Neighbors (KNN) classifiers were implemented.
- **Model Evaluation:**  
  - Performance metrics such as accuracy, confusion matrix, and others are used to assess the models.

---

## **How to Run the Notebook**

1. **Requirements**
   - Python 3.x
   - Jupyter Notebook
   - pandas
   - numpy
   - scikit-learn
   - matplotlib
   - seaborn

2. **Steps**
   - Clone or download this repository.
   - Open `IML_Project_12.ipynb` in Jupyter Notebook.
   - Run the notebook cells sequentially to reproduce the analysis and results.

---

## **Key Features and Methods**

- **Exploratory Data Analysis (EDA):**  
  The notebook provides descriptive statistics and visualizations to understand the distribution and relationships in the data.

- **Preprocessing:**  
  - Missing values are identified and handled.
  - Categorical variables are encoded for model compatibility.
  - Features are normalized to ensure fair model training.

- **Model Training:**  
  - Logistic Regression and KNN models are trained on the preprocessed data.
  - The models are evaluated on their ability to predict loan approval status.

- **Interpretability:**  
  Feature importance and model interpretability are discussed, enabling insights into which features most influence the loan approval decision.

---

## **Results**

- The notebook shows the performance of both Logistic Regression and KNN classifiers on the dataset.
- Feature importance analysis helps identify the most influential factors in loan approval decisions.

---

## **Usage**

This project serves as a template for:
- End-to-end supervised machine learning workflows.
- Data preprocessing and feature engineering for tabular datasets.
- Model evaluation and interpretation in financial decision-making contexts.

---

## **References**

- The notebook and code are inspired by standard data science and machine learning practices, including those found in open-source educational resources.

---

## **Acknowledgments**

- Dataset and problem statement provided as part of an interpretability and machine learning course project.
- Libraries used: pandas, numpy, scikit-learn, matplotlib, seaborn.

---

## **Contact**

For questions or contributions, please open an issue or submit a pull request.

---

