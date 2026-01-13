# Financial-Fraud-Project

## Overview
This project focuses on building and evaluating **financial fraud detection models** using firm-level accounting data.  
The objective is to identify **key accounting risk indicators** associated with fraudulent financial reporting and to assess the performance of statistical and machine learning classifiers under **imbalanced data conditions**.

The project emphasises **model interpretability, evaluation rigor, and practical fraud analytics**, reflecting real-world risk and compliance use cases.

---

## Dataset
- File: `Fraud.csv`
- Observation level: Firm-year observations
- Target variable: Fraud indicator (binary classification)

**Key variable groups include:**
- Receivables and revenue-related measures  
- Inventory-related measures  
- Financing and leverage indicators  
- Profitability and performance metrics  

The dataset exhibits **class imbalance**, which mirrors real-world fraud detection challenges.

---

## Methodology

### 1. Data Preparation
- Loaded and cleaned raw accounting data
- Handled missing values and ensured consistent data types
- Prepared features for classification modelling
- Examined class imbalance in the fraud label

### 2. Fraud Detection Models
The following supervised learning models were implemented:

- **Logistic Regression**
  - Baseline statistical model for fraud prediction
  - Focus on interpretability and coefficient analysis

- **Decision Tree**
  - Non-linear classifier to capture interaction effects
  - Used to identify intuitive decision rules

- **K-Nearest Neighbour (KNN)**
  - Distance-based classifier for comparison with parametric models

These models were selected to balance **predictive performance** and **explainability**, which is critical in fraud analytics.

---

## Model Evaluation
Models were evaluated using metrics suitable for **imbalanced classification problems**, including:

- ROC-AUC
- Confusion Matrix
- Classification accuracy comparison

Evaluation focused on:
- Trade-offs between false positives and false negatives
- Model robustness under class imbalance
- Relative performance across different classifiers

---

## Key Insights
- Accounting variables related to **receivables, inventory, and financing activities** are strong indicators of fraud risk
- Logistic regression provides strong baseline performance with high interpretability
- Tree-based models help reveal non-linear fraud patterns but require careful tuning
- Standard accuracy alone is insufficient for fraud detection; ROC-AUC provides more meaningful insight

---

## Tools & Technologies
- **Programming:** Python  
- **Libraries:** pandas, NumPy, scikit-learn, matplotlib, seaborn  
- **Techniques:** Classification modelling, fraud analytics, model evaluation  
- **Workflow:** Data cleaning, feature preparation, modelling, interpretation

---

## Skills Demonstrated
- Financial fraud analytics and risk modelling
- Classification using statistical and machine learning techniques
- Handling and evaluating imbalanced datasets
- Interpreting model outputs for business and compliance insights
- Translating accounting data into actionable fraud risk indicators

---

## How to Run
1. Place `Fraud.csv` in the project root directory
2. Open and run `Financial Fraud Project.ipynb`
3. Execute cells sequentially to reproduce data preparation, modelling, and evaluation results

---


