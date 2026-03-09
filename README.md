# Credit Wise – Loan Approval Prediction

## Overview
Credit Wise is a machine learning project that predicts whether a loan application will be approved or not based on applicant financial and demographic information.

The project includes data preprocessing, exploratory data analysis (EDA), feature engineering, and training multiple machine learning models to analyze loan approval patterns.

The objective of this project is to understand the factors that influence loan approval decisions and build models that can classify applications as approved or rejected.

---

## Dataset
The dataset contains loan application records with multiple features describing the financial status and personal details of applicants.

Some important features include:

- Applicant Income
- Coapplicant Income
- Credit Score
- Debt-to-Income Ratio (DTI)
- Savings
- Loan Amount
- Loan Term
- Employment Status
- Education Level
- Property Area

### Target Variable

Loan_Approved  
- Yes  
- No  

---

## Project Workflow

### 1. Data Loading
The dataset is loaded using **Pandas** for analysis and preprocessing.

### 2. Data Cleaning
Missing values were handled using:
- Mean imputation for numerical columns
- Most frequent value for categorical columns

### 3. Exploratory Data Analysis (EDA)

Several visualizations were created to understand the dataset:

- Loan approval distribution
- Gender distribution
- Education level distribution
- Income distributions
- Credit score analysis
- Boxplots for detecting outliers
- Correlation heatmap

These visualizations help identify relationships between features and loan approval.

### 4. Feature Engineering

Feature transformations were applied to improve model performance.

**Label Encoding**
- Education Level
- Loan Approved

**One Hot Encoding**
- Employment Status
- Marital Status
- Loan Purpose
- Property Area
- Gender
- Employer Category

Additional polynomial features were also created:

- DTI Ratio squared
- Credit Score squared

### 5. Train Test Split

The dataset was divided into:

- 80% Training Data
- 20% Testing Data

Feature scaling was applied using **StandardScaler**.

---

## Machine Learning Models Used

The following classification models were trained:

### Logistic Regression
A linear model commonly used for binary classification problems.

### K-Nearest Neighbors (KNN)
A distance-based model that classifies data based on nearest neighbors.

### Gaussian Naive Bayes
A probabilistic classification algorithm based on Bayes theorem.

---

## Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

These metrics help evaluate the performance and reliability of the models.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Future Improvements

Possible improvements include:

- Hyperparameter tuning
- Trying advanced models such as Random Forest and XGBoost
- Feature selection techniques
- Model deployment using Flask or FastAPI
- Building a web interface for predictions

---

## Author

Haneesh Cholam  
B.Tech CSE Student
