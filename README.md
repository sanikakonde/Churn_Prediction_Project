# Telco Customer Churn Prediction

## About the Project

Customer churn means when a customer stops using a company's service.

In this project, I built a **Customer Churn Prediction** machine learning model using the Telco Customer Churn dataset.

The main goal of this project is to understand the customer data, perform exploratory data analysis (EDA), preprocess the data, and build classification models to predict whether a customer is likely to churn or not.

This project helped me practice **Data Analysis, Data Preprocessing, Feature Engineering, and Machine Learning Classification**.

---

## Dataset

I used the **Telco Customer Churn** dataset from Kaggle.

Dataset link:  
https://www.kaggle.com/datasets/blastchar/telco-customer-churn

The dataset contains information about customers, their services, account details, and whether they left the company.

---

## Project Workflow

The project follows these main steps:

1. Importing Required Libraries
2. Loading the Dataset
3. Understanding the Dataset
4. Identifying Categorical and Numerical Features
5. Exploratory Data Analysis (EDA)
6. Distribution of Categorical Features
7. Distribution of Numerical Features
8. Correlation Analysis
9. Data Preprocessing
10. Train-Test Split
11. Building a Baseline Model
12. Comparing Different Classification Models
13. 5-Fold Stratified Cross-Validation
14. Model Comparison
15. Hyperparameter Tuning
16. Training the Final Model
17. Evaluating the Final Model

---

## Exploratory Data Analysis

I performed EDA to understand the dataset before building the machine learning models.

### Categorical Features

I used count plots to understand the distribution of categorical features such as:

- Gender
- Partner
- Dependents
- Phone Service
- Internet Service
- Online Security
- Online Backup
- Device Protection
- Tech Support
- Streaming TV
- Streaming Movies
- Contract
- Payment Method

### Numerical Features

I used histograms and KDE plots to understand the distribution of numerical features such as:

- SeniorCitizen
- Tenure
- Monthly Charges
- Total Charges

I also checked the correlation between numerical variables.

---

## Data Preprocessing

Before training the models, the data was preprocessed.

The preprocessing steps included:

- Handling missing values
- Separating numerical and categorical features
- Encoding categorical features using One-Hot Encoding
- Scaling numerical features using StandardScaler
- Splitting the dataset into training and testing sets

I used a **Scikit-learn Pipeline and ColumnTransformer** so that preprocessing and model training could be handled together.

---

## Machine Learning Models

I compared different classification models to understand their performance on the customer churn prediction problem.

The models used in the project include classification algorithms such as:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Gradient Boosting Classifier

The models were evaluated using appropriate classification metrics.

---

## Model Evaluation

The models were evaluated using metrics such as:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

I also used **5-Fold Stratified Cross-Validation** to get a more reliable estimate of model performance.

---

## Hyperparameter Tuning

After comparing the models, I performed hyperparameter tuning to improve the selected model.

I used **GridSearchCV** to search for better combinations of model parameters.

The best parameters obtained from the grid search were then used to train the final model.

---

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook / Kaggle Notebook

---

## Project Structure

```text
Telco-Customer-Churn/
│
├── Churn Prediction.ipynb
├── README.md
└── dataset/
