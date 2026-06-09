🏥 Healthcare Analytics: Patient Readmission Prediction

 Project Overview

Hospital readmissions are a significant challenge for healthcare providers, impacting patient outcomes and increasing healthcare costs.
This project leverages machine learning techniques to predict whether a patient is likely to be readmitted within 30 days of discharge.

Using a real-world healthcare dataset containing over 100,000 patient records, this project performs end-to-end data analysis, preprocessing,
exploratory data analysis (EDA), predictive modeling, and business-oriented recommendations to support data-driven healthcare decisions.


🎯 Business Problem

Unplanned hospital readmissions can indicate gaps in patient care and contribute to increased operational costs.

The objective of this project is to:

* Identify patients at high risk of readmission.
* Improve patient care through proactive intervention.
* Support healthcare administrators in resource allocation.
* Reduce avoidable healthcare expenses.



📊 Dataset Information

| Metric                  | Value              |
| ----------------------- | ------------------ |
| Total Records           | 101,766            |
| Total Features          | 50                 |
| Target Variable         | 30-Day Readmission |
| Readmission Rate        | 11.16%             |
| Readmitted Patients     | 11,357             |
| Non-Readmitted Patients | 90,409             |

Dataset Characteristics

* Real-world healthcare patient records
* De-identified patient information
* Mixed categorical and numerical features
* Highly imbalanced target distribution
* Suitable for classification modeling


 🔄 Data Processing Pipeline

Data Cleaning

Missing value identification and treatment
Placeholder (`?`) value handling
Data quality validation
Duplicate record verification

Feature Engineering

* Domain-specific feature evaluation
* Healthcare-related variable analysis
* Derived feature exploration

Categorical Encoding

A total of *9 categorical features* were encoded to make the data suitable for machine learning algorithms.

---

📈 Exploratory Data Analysis

The project includes comprehensive EDA to understand:

# Univariate Analysis

* Patient demographics
* Admission characteristics
* Medication distributions
* Hospital stay patterns

# Bivariate Analysis

* Relationship between features and readmission
* Readmission patterns across patient groups
* Risk factor identification

# Correlation Analysis

* Feature relationships
* Potential predictors
* Data dependencies



# 🤖 Machine Learning Models

Two classification models were trained and evaluated.

1. Logistic Regression

A baseline interpretable model used to understand feature influence and establish benchmark performance.

2. Random Forest Classifier

An ensemble-based model capable of capturing complex relationships within healthcare data.

### Best Performing Model

*Random Forest Classifier*

| Metric    | Score  |
| --------- | ------ |
| ROC-AUC   | 0.6529 |
| Accuracy  | 0.7554 |
| Precision | 0.1949 |
| Recall    | 0.3809 |



# 📊 Model Evaluation Strategy

The following metrics were used due to class imbalance:

* Accuracy
* Precision
* Recall
* ROC-AUC Score
* Confusion Matrix Analysis

Special attention was given to Recall and ROC-AUC since identifying high-risk patients is often more important than maximizing overall accuracy.



📉 Visualizations & Reporting

The project contains:

* 12+ professional visualizations
* Readmission distribution analysis
* Feature relationship plots
* Correlation analysis
* Model performance charts
* Feature importance visualizations
* Executive dashboard


🔍 Key Findings

# Patient Readmission Insights

* Readmission cases represent approximately **11.16%** of the population.
* Several patient and admission-related factors show measurable influence on readmission risk.
* Class imbalance significantly impacts model performance and requires specialized evaluation metrics.
# Predictive Modeling Insights

* Random Forest outperformed Logistic Regression.
* Ensemble methods captured nonlinear healthcare patterns more effectively.
* Feature importance analysis provided actionable clinical insights.


# 💼 Business Value

The predictive system can help healthcare organizations:

# Risk Stratification
Identify high-risk patients before discharge.

# Resource Optimization
Allocate care management resources efficiently.

# Preventive Intervention
Enable targeted follow-up programs for vulnerable patients.

# Cost Reduction
Reduce avoidable readmissions and associated healthcare expenses.



📦 Project Deliverables


# Analytical Deliverables

* Comprehensive EDA
* Feature importance analysis
* Model comparison study
* Risk scoring framework

# Business Deliverables

* Executive summary
* Actionable recommendations
* Cost-benefit considerations
* Stakeholder-focused reporting


⚙️ Technologies Used

# Programming
* Python

# Data Analysis
* Pandas
* NumPy

# Visualization
* Matplotlib
* Seaborn

# Machine Learning
* Scikit-learn

# Development Tools
* Google colab
* Git
* GitHub





