# Insurance Fraud Detection Using SAS Enterprise Miner 

This is a project designed to detect fraudulent insurance claims using machine learning models that built entirely in no-code platform (SAS Enterprise Miner). 

**Objective:**
Improve fraud detection through predictive modeling and business insights, helping insurers reduce losses and streamline claims processing.

## Overview
This project uses an insurance claims dataset from Kaggle (https://www.kaggle.com/datasets/arpan129/insurance-fraud-detection/data) to predict fraudulent behavior using:
- Decision Trees
- Gradient Boosting
- Logistic Regression
- Ensemble Model

These entire models development was done using **SAS Enterprise Miner**, demonstrating my ability to apply the **CRISP-DM framework** and deliver business value without code.

## Business Goal and Project Objectives
### Business Goal
The primary business goal of this project is to develop a fraud detection system that can improves the acciracy and efficiency of identifying fraudulent insurance claims.
By leveraging predictive analytics, this system aims to:
- Reduce financial losses caused by undetected fraud
- Enhance risk assessment and decision-making processes
- Improve operational efficiency in claims handling

### Project Objectives
To achieve the business goal, this project focused on:
1. To develop a predictive model that identgfy fraudulent claims using machine learning within no-code platform (SAS EM).
2. To investigate key fraud risk factors and assess their impacts on model precision and interpretability.
3. To evaluate and compare multiple predictive models.
4. To suggest actionable recommendations that may improve fraud detection systems based on data-driven insights.

## What I did
As an analyst, I:
- Explore an end-to-end Machine Learning pipeline using no-code platform.
- Balanced imbalanced data using sampling techniques.
- Interpreted model results to uncover fraud signals.
- Suggested business-focused solutions to improve claims operations.

## Project Methodology (CRISP-DM)
| Step | Description |
|------|-------------|
| **Business Understanding** | Defined how fraud harms insurers and why predictive modeling is needed |
| **Data Understanding** | Explored 39 features including customer info, claim types, and policy limits |
| **Data Preparation** | - Handled missing values (tree-based imputation)<br>- Balanced class labels<br>- Dropped low-importance features |
| **Modeling** | Trained:<br> - Decision Trees<br> - Gradient Boosting<br> - Logistic Regression<br> - Ensemble Model |
| **Evaluation** | Compared models using misclassification and false positive/negative rates |
| **Deployment** | Delivered insights and fraud risk criteria to guide business decisions |

---

## Project Workflow (SAS EM)
*A no-code end-to-end pipeline developed in SAS Enterprise Miner*
(Images/SAS EM Process Flow.png)

## Model Performances Summary
| Model                         | Train Error | Test Error | Notes |
|------------------------------|-------------|------------|-------|
| Decision Tree (2-branch)     | 0.150       | 0.129      | Interpretable but less accurate |
| Gradient Boosting            | 0.111       | 0.141      | Best tree-based model |
| Poly Logistic Regression     | 0.129       | 0.151      | Best regression model |
| **Ensemble Model**           | **0.129**   | **0.151**  | Best balance of performance & interpretability |

---

## Business Insights and Strategic Recommendations
1. Prioritize High-Risk Incident Severity
Total Loss and Major Damage claims are statistically linked to higher fraud probability.  
**Recommendation:** Implement stricter verification protocols (e.g., site visits, anomaly detection) and dedicate investigative resources for these high-risk claims.

2. Introduce Risk-Based Screening Based on Customer Traits
Policyholders who report hobbies such as Chess, Cross-Fit, and Video Gaming show higher fraud risk.  
**Recommendation:** Use behavioral patterns in fraud scoring models to flag suspicious claims for deeper validation—while maintaining fairness and avoiding bias.

3. Enhance Verification for Low-Severity Claims with High-Risk Profiles
Minor Damage or Trivial Damage claims, when filed by high-risk individuals, also indicate potential fraud.  
**Recommendation:** Design targeted checks for these combinations before claim approval to reduce false payouts.

---

# License & Usage Notice ⚠️ 

This project is part of my academic and professional portfolio.

> **It is shared publicly for demonstration and learning purposes only. Reuse, redistribution, or commercial use of this content without explicit permission is prohibited.**

If you'd like to reference this work, please contact me directly at **anastasiasllhi@gmail.com**.
