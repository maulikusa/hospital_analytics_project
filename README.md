# 🏥 Hospital Analytics Project  
Enterprise-Grade Clinical, Operational & Financial Analytics Platform

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Power BI](https://img.shields.io/badge/PowerBI-Dashboard-yellow)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)
![License](https://img.shields.io/badge/License-MIT-green)
![Last Commit](https://img.shields.io/github/last-commit/maulikusa/hospital_analytics_project)

---

## 📌 Project Overview  
This project simulates a full **Hospital Analytics Platform** covering:

- **Clinical Analytics** (LOS prediction, readmission risk, patient outcomes)  
- **Operational Analytics** (patient flow, bed utilization, staffing efficiency)  
- **Financial Analytics** (revenue, cost, profitability, payer mix)  
- **Synthetic Data Generation** for patients, encounters, diagnoses, doctors  
- **Python ETL Pipeline** for cleaning, feature engineering, KPI calculation  
- **Power BI Dashboard** for executive-level reporting  

This is designed as a **portfolio-ready, enterprise-grade project** demonstrating skills in Python, SQL, Power BI, and healthcare analytics.

---

## 🏗️ Architecture Diagram (Text-Based)

Raw CSVs
↓
Python ETL (Cleaning, Feature Engineering, KPI Calculation)
↓
Clinical / Operational / Financial Models
↓
Export Clean Data
↓
Power BI Dashboard (KPIs, Trends, Forecasts)


---

## 📂 Folder Structure

hospital_analytics_project/
│
├── clinical_models/
│   └── los_prediction/
│
├── operational_models/
│
├── financial_models/
│
├── python_analysis/
│   ├── 01_load_data.py
│   ├── 02_cleaning.py
│   ├── 03_feature_engineering.py
│   ├── 04_eda.py
│   ├── 05_kpi_calculation.py
│   └── utils/
│
├── data_generation/
│
├── powerbi_dashboard/
│
├── sql_schema/
│
└── docs/


---

## 📊 Power BI Dashboard  
(Place your PBIX file in `powerbi_dashboard/` and add screenshots here.)

---

## 🧠 Machine Learning Models  
- LOS Prediction (Regression)  
- Readmission Risk (Classification)  
- Feature engineering for clinical variables  

---

## 🛠️ Tech Stack  
- **Python** (Pandas, NumPy, Scikit-Learn, Matplotlib)  
- **SQL** (DDL + schema design)  
- **Power BI**  
- **Git & GitHub**  
- **Synthetic Data Generation**  

---

## 🚀 How to Run the Project

pip install -r requirements.txt
python python_analysis/01_load_data.py
python python_analysis/02_cleaning.py
python python_analysis/03_feature_engineering.py
python python_analysis/05_kpi_calculation.py


---

## 📄 License  
This project is licensed under the MIT License.
