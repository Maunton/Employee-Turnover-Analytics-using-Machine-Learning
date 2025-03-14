# Employee-Turnover-Analytics-using-Machine-Learning

This project focuses on predicting employee turnover at Portobello Tech using machine learning techniques. The project involves data analysis, feature engineering, and model evaluation to identify factors contributing to employee attrition and suggest retention strategies.

Project Overview: Portobello Tech's HR department collects various employee data, including satisfaction level, evaluation scores, time at the company, and promotions, to predict turnover. This project aims to build a machine learning pipeline to evaluate and predict which employees are likely to leave the company.

Key Steps Involved:

1. Data Quality Checks: Handle missing values and ensure clean data for analysis.
2. Exploratory Data Analysis (EDA): Analyze relationships between factors influencing turnover using heatmaps, distribution plots, and bar charts.
3. Clustering: Perform K-means clustering to identify patterns in employee satisfaction and evaluation scores.
4. Handling Class Imbalance: Use SMOTE for balancing the dataset and improving model performance.
5. Model Training & Evaluation: Train multiple models (Logistic Regression, Random Forest, and Gradient Boosting) using k-fold cross-validation and evaluate using performance metrics such as ROC/AUC and confusion matrix.
6. Retention Strategies: Use the best model to categorize employees into risk zones and suggest retention strategies based on predicted turnover probabilities.

Technologies Used:

Python (Pandas, Scikit-learn, Matplotlib, Seaborn, Imbalanced-learn)

Jupyter Notebooks for analysis and visualization

Dataset Source:

Kaggle: https://www.kaggle.com/datasets/liujiaqi/hr-comma-sepcsv
