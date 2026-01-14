# 🏦 Bank Data Analysis Dashboard

## 📌 Project Overview
This project provides a comprehensive analysis of banking operations using customer, loan, and deposit data. The objective is to derive **actionable financial insights** by combining **data engineering, exploratory data analysis (EDA), and interactive dashboards**.

The project follows a complete analytics pipeline:
- Data collection using **Excel**
- Data storage and querying using **MySQL**
- Exploratory Data Analysis using **Python**
- Business intelligence dashboards built using **Power BI**

---

## 🗂️ Data Collection & Storage
- **Source:** Excel-based banking dataset
- Data includes customer demographics, account types, loans, deposits, income bands, occupations, nationalities, and bank relationships.
- Cleaned data was dumped into **MySQL** for structured storage and querying.

---

## 🛠️ Tech Stack
- **Excel** – Data collection and initial preprocessing  
- **MySQL** – Data storage and querying  
- **Python** – Exploratory Data Analysis (Pandas, NumPy, Matplotlib, Seaborn)  
- **Power BI** – Interactive dashboards and reporting  

---

## 🔄 Project Workflow

### 1️⃣ Data Collection (Excel)
- Collected structured banking data related to customers, loans, deposits, and account balances.

### 2️⃣ Data Storage (MySQL)
- Imported Excel data into MySQL tables.
- Enabled structured querying and reliable data management.

### 3️⃣ Exploratory Data Analysis (Python)
- Performed EDA to:
  - Analyze distributions of loans and deposits
  - Identify customer behavior patterns
  - Validate trends across income bands, occupations, and nationalities

### 4️⃣ Dashboard Development (Power BI)
- Built multiple dashboards for focused analysis:
  - Home
  - Loan Analysis
  - Deposit Analysis
  - Summary

---

## 📊 Dashboard Analysis & Insights

## 🏠 Dashboard (HOME)
![Home Dashboard](Dashboard(HOME).png)

### Key Metrics
- **Total Clients:** 3K  
- **Total Loan:** 4.38bn  
- **Total Deposit:** 3.77bn  
- **Checking Accounts:** 963.28M  
- **Savings Accounts:** 698.73M  
- **Business Lending:** 2.60bn  

📌 *Insight:* Business lending contributes a major portion of total loans, indicating strong corporate or SME engagement.

---

## 💳 Dashboard (LOAN ANALYSIS)
![Loan Analysis Dashboard](Dashboard(LOAN ANALYSIS).png)

### Key Insights
- **Bank Loan Total:** 1.77bn  
- **Private Banks** contribute the highest loan volume, followed by Retail and Commercial banks.
- **Loan by Income Band:**
  - Mid-income customers contribute **~53%** of total loans.
- **Loan by Occupation:**
  - Web Developers and IT professionals show the highest loan uptake.
- **Loan by Nationality:**
  - European and Asian customers dominate loan volumes.

📌 *Insight:* Mid-income and tech-based professionals are the most credit-active segments.

---

## 💰 Dashboard (DEPOSIT ANALYSIS)
![Deposit Analysis Dashboard](Dashboard(DEPOSIT ANALYSIS).png)

### Key Insights
- **Bank Deposits:** 2.01bn  
- **Savings Account Amount:** 698.73M  
- **Checking Account Amount:** 963.28M  
- **Deposit by Bank Relationship:**
  - Private Banks lead in total deposits.
- **Deposit by Income Band:**
  - Mid-income customers contribute **~54%** of total deposits.
- **Deposit by Occupation:**
  - IT and development-related professions dominate deposit volumes.

📌 *Insight:* Deposit behavior closely aligns with loan behavior, reinforcing the importance of mid-income professionals.

---

## 📑 Dashboard (SUMMARY)
![Summary Dashboard](Dashboard(SUMMARY).png)

### Consolidated View
- **Total Clients:** 3K  
- **Total Loan:** 4.38bn  
- **Total Deposits:** 3.77bn  
- **Foreign Currency Amount:** 89.65M  
- **Engagement Account Amount:** 513.92M  
- **Total CC Amount:** 9.53M  

📌 *Insight:* Strong engagement and diversified account holdings indicate a well-balanced banking portfolio.

---

## 📌 Business Value
- Helps banks understand **customer financial behavior**
- Identifies **high-value income groups and occupations**
- Supports strategic planning for **loan and deposit products**
- Enables executive-level decision-making through visual insights

---

## 🚀 Future Enhancements
- Predictive modeling for loan default risk  
- Customer segmentation using clustering  
- Time-series analysis on yearly financial trends  
- Automated ETL pipeline for real-time dashboards  

---

## 👤 Author
**Rishabh Verma**  
B.Tech Computer Science | Data Analytics & Business Intelligence  
📍 New Delhi, India  

🔗 LinkedIn: https://www.linkedin.com/in/rishabh-verma-58489026a/
