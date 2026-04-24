# Employee Turnover Analytics using Machine Learning

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![Scikit--Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange)
![SMOTE](https://img.shields.io/badge/SMOTE-Class%20Balancing-purple)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![Status](https://img.shields.io/badge/Status-Portfolio%20Project-brightgreen)

## Overview

This project is an end-to-end **employee turnover analytics and machine learning case study**. The goal is to analyze employee data, identify patterns associated with attrition, train machine learning models, and translate the results into practical retention strategies.

The project uses employee satisfaction, evaluation scores, project load, work hours, tenure, salary level, department, promotion history, and work accident history to understand which employees are more likely to leave.

## Business Problem

Employee turnover is expensive. Losing experienced employees can increase hiring costs, reduce productivity, damage team morale, and create operational risk.

This project answers a realistic HR analytics question:

> Can machine learning help identify employees who may be at risk of leaving, and can those predictions be translated into targeted retention strategies?

## Project Objectives

- Perform data quality checks on the HR dataset.
- Explore relationships between employee behavior and turnover.
- Visualize attrition patterns using charts and correlation analysis.
- Use clustering to identify employee behavior groups.
- Handle class imbalance using SMOTE.
- Train and compare machine learning classification models.
- Evaluate model performance using appropriate classification metrics.
- Categorize employees into retention risk zones.
- Convert technical model output into business recommendations.

## Dataset

The dataset contains employee-related HR features including:

- Satisfaction level
- Last evaluation score
- Number of projects
- Average monthly hours
- Time spent at company
- Work accident history
- Promotion in the last 5 years
- Department
- Salary level
- Turnover label

The target variable is:

```text
left
```

Where:

```text
0 = employee stayed
1 = employee left
```

## Tools and Technologies

| Tool / Library | Purpose |
|---|---|
| Python | Core programming language |
| Pandas | Data loading, cleaning, and analysis |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualizations |
| Scikit-learn | Machine learning models and metrics |
| Imbalanced-learn / SMOTE | Class imbalance handling |
| KMeans | Employee behavior clustering |
| Jupyter Notebook | Development and analysis environment |
| GitHub | Project documentation and version control |

## Machine Learning Workflow

```text
Data Loading
    ↓
Data Quality Checks
    ↓
Exploratory Data Analysis
    ↓
Feature Encoding
    ↓
Clustering Analysis
    ↓
Train/Test Split
    ↓
SMOTE Class Balancing
    ↓
Model Training
    ↓
Model Evaluation
    ↓
Retention Risk Categorization
    ↓
Business Strategy Recommendations
```

## Key Techniques Used

- Data inspection and missing value checks
- Exploratory data analysis
- Correlation heatmap analysis
- Department and salary encoding
- KMeans clustering
- Train/test split
- SMOTE oversampling
- Logistic Regression
- Random Forest
- Gradient Boosting
- Confusion matrix evaluation
- Precision, recall, F1-score, accuracy, and ROC/AUC
- Risk-zone categorization based on predicted probabilities

## Step-by-Step Walkthrough

### 1. Project Files

The repository contains the main notebook, README documentation, and screenshot assets used to explain the project workflow.

![Project Files](images/01-project-files.png)

### 2. Imports and Machine Learning Libraries

The notebook imports the libraries required for data analysis, visualization, clustering, class balancing, model training, and model evaluation.

![Imports and ML Libraries](images/02-imports-and-ml-libraries.png)

### 3. Dataset Preview

The project begins by loading the HR dataset and reviewing the first rows to understand the available features.

![Dataset Preview](images/03-dataset-preview.png)

### 4. Data Quality Checks

The notebook checks the structure of the dataset, confirms data types, and verifies missing values before modeling.

![Data Quality Checks](images/04-data-quality-checks.png)

### 5. Exploratory Data Analysis

Correlation analysis is used to inspect relationships between features and employee turnover.

![EDA Correlation Heatmap](images/05-eda-correlation-heatmap.png)

### 6. Employee Turnover Distribution

The project visualizes turnover behavior to better understand attrition patterns and class balance.

![Employee Turnover Distribution 1](images/06-employee-turnover-distribution1.png)

![Employee Turnover Distribution 2](images/06-employee-turnover-distribution2.png)

### 7. KMeans Clustering

KMeans clustering is used to group employees based on behavior patterns such as satisfaction level and evaluation score.

![KMeans Clustering](images/07-kmeans-clustering.png)

### 8. SMOTE Class Balancing

SMOTE is applied to help address class imbalance and improve model training for turnover prediction.

![SMOTE Class Balancing](images/08-smote-class-balancing.png)

### 9. Model Comparison Results

The project compares multiple classification models and evaluates their ability to predict employee turnover.

![Model Comparison Results](images/09-model-comparison-results.png)

### 10. Retention Risk Strategy

Employees are categorized into retention risk zones based on predicted turnover probability.

![Risk Zone Retention Strategy 1](images/10-risk-zone-retention-strategy1.png)

![Risk Zone Retention Strategy 2](images/10-risk-zone-retention-strategy2.png)

![Risk Zone Retention Strategy 3](images/10-risk-zone-retention-strategy3.png)

## Model Evaluation

The project compares multiple machine learning models:

| Model | Purpose |
|---|---|
| Logistic Regression | Baseline interpretable classification model |
| Random Forest | Ensemble model for improved predictive performance |
| Gradient Boosting | Boosted ensemble model for comparison |

Evaluation metrics include:

- Accuracy
- Precision
- Recall
- F1-score
- ROC/AUC
- Confusion Matrix

> Note: Exact metric values should be updated directly from the final notebook output after rerunning the notebook.

## Retention Zone Output

The notebook categorizes employees into retention zones:

| Retention Zone | Count |
|---|---:|
| Safe Zone | 2,151 |
| High-Risk Zone | 655 |
| Low-Risk Zone | 139 |
| Medium-Risk Zone | 55 |

These risk zones help translate machine learning predictions into business action.

## Key Business Insights

This project shows how machine learning can support HR decision-making by helping identify:

- Employees who may be at high risk of leaving.
- Groups of employees with similar satisfaction and performance patterns.
- Areas where workload, satisfaction, evaluation, salary, or tenure may influence attrition.
- Opportunities for targeted retention strategies instead of broad, generic HR interventions.

## Retention Strategy Recommendations

| Risk Zone | Recommended Action |
|---|---|
| Safe Zone | Maintain engagement, recognize strong performers, and continue normal retention practices. |
| Low-Risk Zone | Monitor satisfaction and workload trends before they become larger issues. |
| Medium-Risk Zone | Conduct manager check-ins, review workload, and identify career development needs. |
| High-Risk Zone | Prioritize retention conversations, compensation review, workload adjustment, and career path planning. |

## What Employers Should Notice

This project demonstrates more than basic notebook work. It shows the ability to move from raw data to business recommendations.

Key strengths demonstrated:

- End-to-end machine learning workflow.
- Data inspection and cleaning.
- Exploratory data analysis.
- Clustering and segmentation.
- Handling imbalanced classification data with SMOTE.
- Training and comparing multiple ML models.
- Evaluating classification performance with appropriate metrics.
- Translating predictions into actionable retention strategies.
- Communicating technical work clearly for both technical and non-technical audiences.
- Building a GitHub portfolio project with clean documentation and visual evidence.

## Why This Project Matters

This project is valuable because it connects technical machine learning work to a real business problem: reducing employee turnover.

A model is only useful if decision-makers can act on it. This project demonstrates the ability to not only build models, but also explain how the results could support better business decisions.

## Lessons Learned

- Data quality checks are essential before modeling.
- Class imbalance can affect model performance and should be handled carefully.
- Different models may perform differently depending on the business goal.
- Recall is especially important when identifying employees at risk of leaving.
- Visualizations help communicate patterns that raw numbers may hide.
- Machine learning results become more valuable when translated into business strategy.

## Future Improvements

- Add a model metrics table directly in the README after rerunning the notebook.
- Add feature importance analysis from the Random Forest model.
- Add ROC curve screenshots for model comparison.
- Add SHAP values for explainability.
- Convert the notebook into a reproducible Python pipeline.
- Add a Streamlit dashboard for HR-style interaction.
- Add a prediction form for new employee records.
- Save the trained model using `joblib`.
- Add a requirements.txt file.
- Add a short demo GIF showing the notebook workflow.

## Disclaimer

This project is for educational and portfolio purposes only. The dataset is used for machine learning practice and should not be used to make real employment decisions without proper validation, fairness review, privacy review, and organizational oversight.
