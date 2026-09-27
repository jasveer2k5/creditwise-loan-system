CreditWise -- Loan Approval Prediction System

A Machine Learning-based loan approval prediction system built with
Python and Scikit-learn.

Overview-

CreditWise is an end-to-end machine learning project for analyzing loan
application data and predicting loan approval outcomes. It covers data
preprocessing, exploratory data analysis, categorical encoding, feature
scaling, feature engineering, model training, and evaluation.

Problem Statement-

Loan approval depends on multiple applicant and financial factors. The
objective of CreditWise is to use historical loan application data to
build classification models that predict whether a loan application is
likely to be approved or rejected.

Dataset-

The project uses loan_approval_data.csv.

Key data areas include applicant income, coapplicant income, credit
score, DTI ratio, savings, education level, employment status, marital
status, loan purpose, property area, gender, employer category, and loan
approval status. Applicant_ID is removed before model training because
it is an identifier.

Tools and Technologies-

Python
NumPy
Pandas
Scikit-learn
Matplotlib
Seaborn
Jupyter Notebook / Anaconda
Git & GitHub
Methods
Data Preprocessing: Missing numerical values were handled with
mean imputation and categorical values with most-frequent
imputation.
EDA: Class distribution, categorical distributions, income
histograms, boxplots, and correlation analysis were performed.
Encoding: LabelEncoder and OneHotEncoder were used for
categorical variables.
Scaling: StandardScaler was used for numerical features.
Models: Logistic Regression, K-Nearest Neighbors (KNN), and
Gaussian Naive Bayes.
Feature Engineering: DTI_Ratio_sq = DTI_Ratio² and
Credit_Score_sq = Credit_Score².
Evaluation: Accuracy, Precision, Recall, F1-Score, and Confusion
Matrix.
Key Insights
Loan approval depends on a combination of financial and
applicant-related features.
EDA helps identify distributions, outliers, and relationships in the
data.
Different classification algorithms produce different performance
across evaluation metrics.
Feature engineering can help capture nonlinear relationships.
Precision, Recall, and F1-Score provide additional insight beyond
accuracy.

Dashboard-

The project can be presented through a simple dashboard containing: -
Total loan records - Approved and rejected loan counts - Loan approval
distribution - Feature correlation heatmap - Model performance
comparison - Confusion matrix - Loan prediction interface - Dataset
preview/upload section
    
Result & Conclusion-

CreditWise demonstrates an end-to-end machine learning workflow for loan
approval prediction, combining preprocessing, visualization, encoding,
scaling, feature engineering, classification models, and multiple
evaluation metrics.

Future Work-

Hyperparameter tuning and cross-validation
Additional classification algorithms
Improved class-imbalance handling
Advanced feature engineering
Model explainability with SHAP
Model persistence with Joblib
Production deployment
Model monitoring

Author & Contact-

Jasveer Singh
B.Tech -- Artificial Intelligence & Machine Learning

GitHub: https://github.com/jasveer2k5
LinkedIn: www.linkedin.com/in/jasveersingh2k5
Email: your- jasveer2k5@gmail.com

CreditWise -- Loan Approval Prediction System
Built with Python, Pandas, NumPy, Scikit-learn, Matplotlib, and Seaborn.
