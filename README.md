<div align="center">

# Financial Transaction Fraud Risk Prediction

### Machine Learning and Data Mining for Fraud Detection

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-F7931E?logo=scikitlearn)
![Data Mining](https://img.shields.io/badge/Data%20Mining-Classification-informational)

**Academic Project · Data Mining · Classification · Financial Risk Analytics**

[Open Google Colab Notebook](https://colab.research.google.com/drive/1Iz2nfMgBLZl4bl1T7bCW_HMK0BbqVQAe?usp=sharing)

</div>

---

## Project Highlights

| Component | Description |
|---|---|
| Domain | Financial Fraud Analytics |
| Task | Binary Classification |
| Target | Fraud vs Non-Fraud |
| Data Challenge | Class Imbalance |
| Modeling | Multiple Supervised Classification Algorithms |
| Evaluation | Accuracy, Precision, Recall, F1-Score |
| Project Type | Academic Data Mining Final Project |
| Year | 2025 |

> **Project focus:** Identifying transaction patterns associated with fraud risk while evaluating classification performance beyond accuracy in an imbalanced financial dataset.

---

## Overview

This project explores the use of **machine learning and data mining techniques** to identify potentially fraudulent financial transactions based on transaction characteristics and behavioral indicators.

The analytical workflow covers:

- Data cleaning and preprocessing
- Exploratory data analysis
- Feature preparation
- Class imbalance analysis
- Classification modeling
- Model comparison
- Performance evaluation
- Fraud pattern interpretation

The project was developed as a **Data Mining final assignment** and should be interpreted as an academic fraud detection study rather than a production banking fraud detection system.

---

## Problem Context

Fraud detection presents a challenging machine learning problem because fraudulent transactions typically represent a much smaller proportion of the data than legitimate transactions.

This imbalance creates an important analytical issue:

```text
High Accuracy ≠ Effective Fraud Detection
```

A model may achieve high overall accuracy while still failing to correctly identify fraudulent transactions.

For this reason, the project emphasizes not only accuracy but also:

- Precision
- Recall
- F1-Score
- False positive considerations
- False negative considerations

The objective is to evaluate whether transaction characteristics can provide useful signals for distinguishing potentially fraudulent activity from legitimate behavior.

---

## Project Objectives

The project was designed to:

- Explore transaction characteristics associated with fraudulent activity.
- Prepare financial transaction data for supervised classification.
- Develop multiple fraud classification models.
- Compare model behavior across different algorithms.
- Evaluate model performance using classification metrics.
- Examine the impact of class imbalance on fraud prediction.
- Generate interpretable analytical insights from model results.

---

## Dataset Overview

| Attribute | Description |
|---|---|
| Domain | Financial Transaction Analytics |
| Target Variable | Fraud vs Non-Fraud |
| Problem Type | Binary Classification |
| Key Information | Transaction characteristics and behavioral indicators |
| Data Characteristic | Imbalanced class distribution |
| Application Context | Fraud Detection and Financial Risk Analytics |

### Representative Feature Categories

The analysis considers transaction-related characteristics such as:

- Transaction amount
- Transaction frequency
- Behavioral indicators
- Customer activity patterns
- Other transaction-level attributes available in the dataset

> The specific predictive value of each feature depends on the dataset and the preprocessing applied during the experiment.

---

## Methodology

The project follows a structured data mining workflow:

```text
Raw Transaction Data
        │
        ▼
Data Cleaning
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Feature Preparation
        │
        ▼
Class Distribution Analysis
        │
        ▼
Machine Learning Modeling
        │
        ▼
Model Evaluation
        │
        ▼
Fraud Pattern Interpretation
```

---

## 1. Data Preparation

The first stage focuses on preparing transaction data for analysis and modeling.

The workflow includes:

- Inspecting data structure
- Handling missing or inconsistent values
- Preparing numerical and categorical variables
- Reviewing class distribution
- Preparing features and target variables
- Structuring the dataset for model training and evaluation

Careful preprocessing is particularly important in fraud detection because noisy or poorly prepared data can substantially affect classification performance.

---

## 2. Exploratory Data Analysis

Exploratory analysis was performed to understand:

- Transaction distributions
- Fraud and non-fraud class proportions
- Behavioral patterns
- Potentially informative features
- Outliers and unusual transaction characteristics

The EDA stage provides the analytical foundation for subsequent model development.

---

## 3. Classification Modeling

Multiple supervised learning algorithms were evaluated.

Models explored include:

- Logistic Regression
- Decision Tree
- Random Forest
- Additional classification experiments where applicable

Each algorithm provides a different perspective on the fraud classification problem.

### Logistic Regression

Provides an interpretable linear baseline for binary classification.

### Decision Tree

Captures nonlinear decision rules and feature interactions.

### Random Forest

Combines multiple decision trees to improve generalization and reduce the instability of a single tree.

---

## 4. Evaluation Strategy

Fraud detection should not be evaluated using accuracy alone.

The project therefore considers multiple classification metrics.

| Metric | Interpretation |
|---|---|
| Accuracy | Overall proportion of correct predictions |
| Precision | Proportion of predicted fraud cases that are actually fraud |
| Recall | Proportion of actual fraud cases correctly detected |
| F1-Score | Harmonic balance between precision and recall |

### Why Recall Matters

Low recall can result in fraudulent transactions remaining undetected.

### Why Precision Matters

Low precision can generate excessive false fraud alerts.

Effective fraud detection therefore requires balancing the cost of:

```text
False Negative
Fraud is missed

vs.

False Positive
Legitimate transaction is flagged
```

---

## Class Imbalance

One of the primary analytical challenges in this project is the imbalance between fraudulent and legitimate transactions.

```text
Legitimate Transactions
        ███████████████████

Fraudulent Transactions
        ██
```

In an imbalanced dataset, overall accuracy can be misleading.

A model that predicts the majority class most of the time may appear accurate while providing poor fraud detection capability.

For this reason, the experiment emphasizes precision, recall, and F1-score alongside accuracy.

---

## Key Findings

Several observations emerged from the analysis.

### Fraud Detection Requires More Than Accuracy

Class imbalance makes accuracy insufficient as a standalone evaluation metric.

### Model Choice Influences Fraud Detection Behavior

Different algorithms produce different trade-offs between detecting fraudulent transactions and avoiding false alarms.

### Ensemble Modeling Provides a Useful Comparison

Random Forest provided a useful ensemble-based benchmark compared with simpler classification approaches.

### Data Preparation Strongly Influences Results

Preprocessing, feature preparation, and class distribution need to be considered carefully before interpreting classification performance.

### Precision and Recall Represent Different Operational Risks

Higher recall prioritizes detecting more fraudulent transactions, while higher precision reduces unnecessary fraud alerts.

---

## Key Technical Challenge

### Challenge

Fraud detection involves an imbalanced classification problem in which fraudulent transactions represent a smaller portion of the dataset.

This can produce misleading model performance if evaluation relies primarily on accuracy.

### Analytical Approach

The project addresses this issue by:

- Inspecting class distribution
- Preparing transaction features carefully
- Comparing multiple classification models
- Evaluating performance using several metrics
- Interpreting precision and recall together
- Considering the implications of false positives and false negatives

This evaluation framework provides a more meaningful view of model behavior than accuracy alone.

---

## My Contribution

My contribution focused on the machine learning and analytical components of the project.

Responsibilities included:

- Structuring the analytical workflow
- Supporting data preprocessing
- Developing classification models
- Comparing model behavior
- Evaluating model performance
- Interpreting fraud-related patterns
- Generating analytical insights
- Preparing technical documentation
- Collaborating with team members throughout the project

---

## Team

| Name | Primary Contribution |
|---|---|
| **Muhammad Wildan Nabila** | **Project Lead / Machine Learning & Model Evaluation** |
| Hans Adiyatma Putra | Data Preprocessing & Feature Preparation |
| Irawana Juwita | Exploratory Data Analysis & Visualization |

> Contributions are presented according to the primary responsibilities within the academic project.

---

## Potential Practical Relevance

This project is an academic machine learning study rather than a production fraud detection system.

Nevertheless, the analytical concepts explored are relevant to:

- Transaction screening
- Fraud risk analytics
- Financial anomaly detection
- Banking risk monitoring
- Fintech security
- Early fraud warning systems
- Data-driven financial risk assessment

A real-world implementation would require substantially broader validation, security controls, model monitoring, regulatory considerations, and integration with operational transaction systems.

---

## Technology Stack

| Area | Technology |
|---|---|
| Programming | Python |
| Data Manipulation | Pandas, NumPy |
| Machine Learning | Scikit-learn |
| Visualization | Matplotlib |
| Analytical Domain | Data Mining |
| Modeling Task | Binary Classification |
| Development Environment | Google Colab |

---

## Skills Demonstrated

This project demonstrates practical experience in:

- Data Analysis
- Data Mining
- Machine Learning
- Binary Classification
- Fraud Analytics
- Financial Data Analysis
- Exploratory Data Analysis
- Data Preprocessing
- Feature Preparation
- Model Evaluation
- Precision / Recall Analysis
- Python
- Pandas
- Scikit-learn
- Technical Documentation

---

## Limitations

The project should be interpreted within its academic scope.

Key limitations include:

1. **Class imbalance**  
   Fraudulent observations represent a smaller proportion of the dataset.

2. **Dataset dependency**  
   Model behavior depends on the characteristics and quality of the available transaction data.

3. **Limited operational validation**  
   The models have not been evaluated in a live banking or fintech transaction environment.

4. **No real-time fraud infrastructure**  
   The project focuses on offline analytical modeling rather than real-time transaction scoring.

5. **Evaluation scope**  
   Additional metrics and threshold analysis may provide further insight into model behavior.

6. **No production risk controls**  
   The project does not include operational monitoring, regulatory controls, fraud investigation workflows, or production security infrastructure.

These limitations provide clear directions for further development.

---

## Future Development

Potential extensions include:

- SMOTE or alternative resampling techniques
- Cost-sensitive learning
- XGBoost
- LightGBM
- Hyperparameter optimization
- ROC-AUC and PR-AUC evaluation
- Classification threshold optimization
- Confusion matrix analysis
- Feature importance analysis
- SHAP-based model interpretation
- Anomaly detection approaches
- Real-time transaction scoring architecture
- API-based model deployment
- Model monitoring and drift detection

---

## Academic Context

This repository represents a **Data Mining final project completed in 2025**.

The project focuses on applying supervised machine learning techniques to a financial fraud classification problem while emphasizing the methodological challenges associated with imbalanced data.

The primary academic objectives were:

- Applying the data mining workflow
- Developing classification models
- Comparing machine learning approaches
- Evaluating imbalanced classification performance
- Interpreting predictive results

> This repository represents an academic experiment and should not be interpreted as a production banking fraud detection platform.

---

## Notebook

The analysis and modeling workflow can be reviewed in Google Colab:

**[Open Project Notebook](https://colab.research.google.com/drive/1Iz2nfMgBLZl4bl1T7bCW_HMK0BbqVQAe?usp=sharing)**

---

## Project Summary

| Component | Summary |
|---|---|
| Domain | Financial Fraud Analytics |
| Task | Fraud vs Non-Fraud Classification |
| Challenge | Imbalanced Classification |
| Modeling | Logistic Regression, Decision Tree, Random Forest |
| Evaluation | Accuracy, Precision, Recall, F1-Score |
| Environment | Python / Google Colab |
| Project Type | Academic Data Mining Final Project |

This project demonstrates an end-to-end analytical workflow for financial fraud classification, from preprocessing and exploratory analysis to machine learning modeling, evaluation, and fraud risk interpretation.

---

## Author

**Muhammad Wildan Nabila**  
Bachelor of Informatics  
Universitas Muhammadiyah Malang

**Areas of Interest**  
Data Science · Machine Learning · Artificial Intelligence · Data Analytics

---

<div align="center">

### Machine Learning for Data-Driven Financial Risk Analysis

**Data Mining · Classification · Fraud Analytics · Model Evaluation**

</div>
