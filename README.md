# Telecom-Customer-Churn

Overview
This project focuses on predicting customer churn for a telecom company using machine learning techniques. The goal is to identify customers who are likely to churn, enabling the company to take proactive measures to retain them.

Dataset
The dataset used in this project contains 7,043 unique customer records, including various attributes such as customer demographics, account information, and service usage patterns.

Project Workflow
Data Collection and Integration:

Imported and merged customer, churn, and internet service datasets.
Data Preparation:

Conducted extensive data cleaning and handled missing values.
Converted categorical variables to dummy variables.
Exploratory Data Analysis (EDA):

Performed EDA to understand the distribution and relationships of variables.
Identified key factors influencing customer churn.
Feature Engineering:

Created new features and dropped redundant variables to improve model performance.
Addressed outliers in continuous variables to maintain data integrity.
Model Building:

Built and evaluated multiple machine learning models, including Logistic Regression and Decision Trees.
Model Optimization:

Used Recursive Feature Elimination (RFE) and Variance Inflation Factor (VIF) for feature selection and to reduce multicollinearity.
Evaluation and Results:

Conducted ROC curve analysis to determine the optimal cutoff point for the churn prediction model.
Achieved a significant prediction accuracy.
Key Findings
The churn rate was calculated at 27%, indicating an imbalanced dataset.
Logistic Regression and Decision Trees were effective in predicting customer churn.
Key factors influencing churn included contract type, tenure, and monthly charges.
Conclusion
The project successfully demonstrated the application of machine learning techniques to predict customer churn in the telecom sector. The insights gained can help telecom companies develop strategies to reduce churn rates and enhance customer retention.

Dependencies
Python 3.7+
Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn
Usage
To run the project, clone this repository and install the required dependencies. Then, execute the Jupyter notebooks provided in the repository.
