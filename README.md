---

# Fairfax Asia (PIB) Internship: ML Projects

This repository contains two primary machine learning projects developed during my internship with the **ML Team at Fairfax Asia (PIB)**. These projects focus on agent performance analytics and predictive premium pricing.

---

## 🚀 Project 1: Agent Performance Analysis (Scorecard)

**Objective:** To classify and evaluate agent performance over multiple accounting years (2022–2025) using a multi-dimensional scoring matrix.

### Methodology

The analysis utilized **Agent Metadata** and **Reporting Lines** (e.g., KL Agency, PAMP Affinity, Alternative Channel, and Branches) to group data and generate a Final Score.

**Data Quality Assumptions:**

* Non-Zero Net Earned Premium (NEP).


* Positive Net Incurred Claims (NIC).


* Non-Zero number of policies.



### The Scoring Logic

Agents are classified into four quadrants based on their **Final Score** and **NIC/NEP Ratio**:

| Classification | Final Score | NIC/NEP Ratio | Visual Indicator |
| --- | --- | --- | --- |
| **Efficient Performer** | High | Low | ✅ 

 |
| **Low Performer** | Low | Low | ⚠️ 

 |
| **High-Loss Performer** | High | High | 🚩 

 |
| **High-Risk Underperformer** | Low | High | ❌ 

 |


* 
**F1 Score:** 95% 



---

## 📈 Project 2: Premium Pricing Prediction

**Objective:** To develop a predictive model for insurance pricing using historical policy data, moving beyond static risk assessment to dynamic price prediction.

### Model Architecture

* 
**Algorithm:** CATBoost Regressor.


* 
**Training Data:** 1,559,434 Policies from 2020–2022.


* 
**Testing Data:** 166,065 Policies from 2023 & 2024.



### Model Performance

The model demonstrated high stability and accuracy across different temporal datasets over **900 iterations**:

| Dataset | Fit Accuracy |
| --- | --- |
| **Train Fit** | 84.90% 

 |
| **Test Fit (2023)** | 84.12% 

 |
| **Test Fit (2024)** | 81.20% 

 |

---

## 🛠️ Tools & Technologies

* **Languages:** Python
* 
**Machine Learning:** XGBoost , CATBoost Regressor 


* 
**Data Visualization:** Matplotlib/Seaborn for Agent Trend Analysis 


* 
**Domain:** General Insurance (PIB) 



---

*Developed during my internship at Fairfax Asia (ML Team – PIB).* 

---

