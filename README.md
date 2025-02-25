# Credit-EDA-Analysis
Project Title: Credit EDA and Scoring Using Machine Learning

Project Overview: This project focuses on performing Exploratory Data Analysis (EDA) and building a credit scoring model using a dataset with various financial and demographic features. The goal is to analyze customer credit profiles, identify key risk factors, and develop a predictive model to estimate a hypothetical credit score based on the dataset.

Key Objectives:

Exploratory Data Analysis (EDA): Analyze and visualize the dataset to uncover patterns and trends in customer credit behavior.

Feature Engineering: Create new features and modify existing ones to improve the accuracy and performance of the credit scoring model.

Credit Scoring Model: Build a model to predict a credit score for customers, providing a risk assessment of creditworthiness.

Risk Mitigation: Identify key risk factors influencing loan approval and provide strategies to mitigate these risks.

Model Evaluation: Evaluate model performance using appropriate metrics (e.g., AUC, accuracy, precision, recall).

Insights and Findings:

Data Overview:

Dataset: The dataset contains 100,000 rows and 27 columns, including demographic and financial information such as income, loan type, credit score, and payment behavior.

Key Features: Age, Income, Credit Mix, Outstanding Debt, Credit Utilization Ratio, Payment Behavior.

Exploratory Data Analysis (EDA):

Missing Data: Identify and impute missing values using mean, median, or forward/backward fill as appropriate.

Correlation Analysis: Find key correlations between features like Credit Utilization Ratio, Outstanding Debt, and Credit Score.

Visualizations: Use histograms, box plots, and heatmaps to visualize distributions and relationships between features.

Outliers: Detect and handle outliers in financial features like Outstanding Debt and Income using Z-score and IQR methods.

Feature Engineering:

Debt-to-Income Ratio (DTI): Create a new feature combining Outstanding Debt and Income to better assess customer debt risk.

Loan-to-Value (LTV): Create an LTV ratio based on the customer's loan amount and property value, which is a strong predictor of default.

Technologies Used:

Programming Language: Python

Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

Tools: Jupyter Notebook
