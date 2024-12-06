# IntroToDS_Project_03
# Telco Customer Churn Prediction

## Project Description
This project aims to predict customer churn in a telecommunication company using machine learning techniques. Customer churn refers to when a customer stops doing business with a company. By analyzing key customer attributes and service features, the project seeks to identify patterns and build predictive models to aid in churn reduction strategies.

## Features
- **Data Preprocessing:** Handled missing values, removed duplicates, and processed categorical and numerical variables.
- **Exploratory Data Analysis (EDA):** Visualized customer attributes and their relationship with churn using bar plots, count plots, and heatmaps.
- **Feature Engineering:** Performed outlier detection, normalization, and feature selection using statistical tests like Chi-Square and ANOVA.
- **Modeling:** Evaluated multiple machine learning models, including:
  - Logistic Regression
  - Naive Bayes
  - Random Forest
  - XGBoost
- **Data Balancing:** Applied SMOTE (Synthetic Minority Oversampling Technique) to balance the dataset.
- **Hyperparameter Tuning:** Performed grid search to optimize Logistic Regression and XGBoost models.

## Technologies Used
- Python
- Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Imbalanced-learn, XGBoost

## Dataset

- **Key Features:**
  - Customer information (e.g., Senior Citizen, Partner, Dependents)
  - Services signed up for (e.g., InternetService, OnlineSecurity)
  - Payment information (e.g., Contract type, PaymentMethod)
  - Monthly and total charges
  - Target variable: `Churn` (Yes/No)
  
## Results
- Evaluated multiple models with cross-validation.
- Best model: (e.g., Logistic Regression with tuned hyperparameters achieving 90% accuracy).
- Confusion matrices, classification reports, and ROC curves were used to evaluate performance.
