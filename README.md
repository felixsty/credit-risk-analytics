# Credit Risk Analytics Dissertation (SAS Enterprise Miner)

## Overview
This dissertation investigates the evolution and effectiveness of analytical techniques in credit risk management, using **SAS Enterprise Miner** to implement and compare traditional statistical methods and modern machine learning approaches.  
The focus is on evaluating model performance for improved credit risk assessment and decision-making.

**Achievement:** Scored **Distinction (83/100)** for the dissertation.

---

## Dataset

- Dataset: Credit risk dataset used for analysis (proprietary / anonymized).  
- Columns include:
  - Customer and financial attributes (e.g., age, income, loan history)
  - Target variable: default or non-default
- Dataset file: `data/german_credit_risk.csv`

---

## Data Preparation (SAS Enterprise Miner)

- Pre-processing performed within SAS EM, including:
  - Handling missing values and outliers
  - Creating derived variables for model input
  - Aggregating and transforming data for analysis
- Workflow captured in the SAS EM project file: `project.emp`

---

## Analysis

- Models built and evaluated include:
  - **Logistic Regression**
  - **Decision Tree**
  - **Random Forest**
- Model performance compared using:
  - Accuracy, precision, sensitivity, F1-score, ROC-AUC
- Insights focus on effectiveness of traditional vs. modern techniques, and the benefit of combining methods for better credit risk prediction.

---

## Skills Demonstrated

- SAS Enterprise Miner: workflow creation, model building, and evaluation
- Credit risk analytics: applying traditional and modern techniques
- Analytical thinking: interpreting model performance metrics
- Data preparation and pre-processing: handling real-world financial datasets

---

## Project Structure

```
credit-risk-analytics/
│
├── dissertation.pdf                 # Full dissertation document
├── project.emp                      # SAS Enterprise Miner project file
│
├── data/
│ └── german_credit_risk.csv        # Dataset used
│
├── figures/
│ └── model_comparison.png           # Key figures from findings and analysis
|
└── README.md                        # Project overview
```

---

This repo demonstrates a **complete analytics workflow**:  
**data preparation → model building → analysis → insight generation**
