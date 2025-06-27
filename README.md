# 📊 Data-Driven Pharmacy Optimization at Tamilnadu Co-operative Pharmacy

**Business Name**: Tamilnadu Co-operative Pharmacy  
**Location**: East Veli Street, Madurai  

## 📌 Project Overview

Pharmacies often face challenges in managing inventory, forecasting demand, and minimizing wastage. This project demonstrates how **data analytics** empowered **Tamilnadu Co-operative Pharmacy** to streamline its operations, improve inventory decisions, and boost efficiency using real-time data and machine learning models.

---

## 🧩 Problem Statement

The pharmacy aimed to:
- Optimize stock levels and reduce wastage.
- Forecast seasonal medicine demand.
- Identify near-expiry stock in advance.
- Understand doctor-wise prescription patterns for better inventory planning.

---

## 📥 Data Collection

We collected real-time transaction data from the official portal:

🔗 [Tamil Nadu Co-operative Medical Stores Portal](https://tncoopws.tn.gov.in/medicaljpc/usermanager/youLogin.jsp)

- Data format: PDFs of bills  
- Tools used for extraction: `PyPDF2`, `pdfplumber`  
- Data extracted into Excel for further processing

📊 **Dataset Sample**:  
[Google Sheet Preview](https://docs.google.com/spreadsheets/d/1qMRmSIWhoCjH6jh9y78FnBhAW_8NQ6W6/edit?usp=drive_link&ouid=109363850224639814922&rtpof=true&sd=true)

---

## 🛠️ Tools & Technologies Used

- **Python**, **Pandas**, **Matplotlib**, **scikit-learn**, **statsmodels**
- **PyPDF2**, **pdfplumber**
- **Power BI**
- **Google Colab**

---

## 🧹 Data Pre-processing Steps

- **Cleaning**: Removed noisy characters, standardized dates and names
- **Conversion**: Converted dates, quantities, and prices to proper data types
- **Deduplication**: Removed duplicate entries
- **Validation**: Cross-checked sample entries with original PDFs

---

## 📈 Statistical & Mathematical Analysis

- **Doctor-wise Prescription Patterns**: Identify demand trends per doctor
- **Bill Amount Distribution (Hypothesis Testing)**: Analyze billing behavior and outliers
- **Pareto Analysis (80/20 Rule)**: Highlight top contributing customers
- **Correlation: Quantity vs Discount**: Analyze bulk purchase trends
- **Cohort Analysis**: Study patient retention and repeat purchases
- **Product Life Cycle**: Track sales lifecycle (Intro → Decline)
- **RFM Analysis**: Segment patients by Recency, Frequency, and Monetary value
- **Restock Logic**: Flag items for restocking using sales trends and availability

---

## 🤖 Prediction Models

| Model | Purpose |
|-------|---------|
| **ARIMA** | Forecast overall pharmacy sales |
| **SARIMA** | Predict seasonal medicine demand |
| **Random Forest Classifier** | Predict medicine expiry status |
| **Adherence Prediction** | Predict patient likelihood to continue medication |

---

## 📊 Dashboard

An **interactive Power BI dashboard** was created to visualize key insights from the analysis and prediction models.

- Sales trends
- Doctor-wise prescriptions
- Inventory status
- Forecasts and alerts

🎥 **Dashboard Walkthrough**: [Watch Video](https://drive.google.com/file/d/1TzLw6Na8McX-zzxVVAEEG715MXMozhqj/view?usp=sharing)  
📊 **Power BI Dashboard**: [View Dashboard](https://app.powerbi.com/links/ReA0aFVzoV?ctid=562673cb-3a12-4428-9c2e-82d74fd5889a&pbi_source=linkShare)  
💻 **Colab Code**: [Open Code Files](https://colab.research.google.com/drive/1Ae-iLvD8h7r4AR00UxYPUVCmZUiDxTYt?usp=sharing)

---

## ✅ Conclusion

This project delivered actionable insights into sales, customer behavior, and inventory performance. By leveraging **data analytics** and **machine learning**, Tamilnadu Co-operative Pharmacy can:

- Make smarter restocking decisions  
- Improve inventory turnover  
- Reduce expiry-related losses  
- Forecast demand and patient behavior more accurately  
- Enhance operational efficiency and customer satisfaction

---
