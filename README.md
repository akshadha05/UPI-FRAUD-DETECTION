#  SentinelPay: UPI Fraud Detection & Analytics Platform

---

##  Project Overview

Digital payments in India—especially UPI—have grown rapidly, but this growth has also led to a sharp increase in fraud.

This project was built to identify, analyze, and prevent fraudulent UPI transactions using machine learning and business intelligence, while clearly demonstrating real-world business impact.

SentinelPay is an end-to-end fraud analytics platform that combines:
- Machine Learning for fraud detection  
- Feature engineering to capture risky behavior  
- Power BI dashboards for real-time monitoring and executive reporting  

---

##  Problem Statement

Banks and payment platforms face three major challenges:

1. Detect fraud accurately in highly imbalanced transaction data  
2. Minimize false positives to avoid blocking genuine customers  
3. Communicate insights clearly to operations teams and decision-makers  

This project addresses all three by integrating ML models with interactive analytics dashboards.

---

##  Solution Architecture

### 1️⃣ Data Layer
- Generated 10,000 synthetic UPI transactions
- Realistic class imbalance: 2% Fraud | 98% Legitimate
- Features include transaction amount, timestamp, merchant category, location, and customer behavior

---

### 2️⃣ Feature Engineering
- Temporal features: Hour of day, day of week, time period  
- Behavioral features: Customer average spend, transaction frequency, deviation  
- Risk indicators: High-risk time windows, high-value transactions, suspicious categories  

---

### 3️⃣ Machine Learning Layer
Models implemented:
- XGBoost  
- Random Forest  
- Ensemble Model  

Evaluation metrics:
- Precision, Recall, F1-Score  
- ROC-AUC  
- Confusion Matrix  

Note: 100% accuracy was achieved due to clearly separable synthetic fraud patterns.  
This was intentional to demonstrate modeling, evaluation, and analytics integration.

---

### 4️⃣ Analytics & Visualization
- 5 interactive Power BI dashboards
- 40+ custom DAX measures
- Real-time fraud monitoring
- Geographic fraud hotspot analysis
- Executive KPI summaries

---

##  Business Impact

###  Financial Impact
- ₹2.85M fraud prevented
- ~1300% ROI (assumed ₹2L system cost)
- Zero false positives, ensuring no customer friction

###  Operational Impact
- Accurate fraud detection on evaluated data
- Faster investigations using drill-through dashboards
- Reduced manual review effort

---

##  Tech Stack

**Programming & ML**
- Python
- Pandas, NumPy
- Scikit-learn, XGBoost

**Visualization**
- Power BI (DAX, Data Modeling)
- Looker Studio

**Tools**
- Google Colab
- GitHub

---



