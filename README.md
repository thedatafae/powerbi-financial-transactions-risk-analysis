# Power BI Financial Transactions & Risk Analysis

## Project Overview
This is a comprehensive **Power BI project** analyzing financial transactions, associated risk incidents, and system/user behavior. The dashboard provides interactive KPIs and visualizations for transaction trends, risk monitoring, and system performance.  

---

## Dataset
The dataset contains simulated financial transactions, risk incidents, and system behavior metrics:

- **Transactions Table:** Transaction_ID, User_ID, Date, Account_Number, Transaction_Type, Amount, Currency, Category, Counterparty, Payment_Method  
- **Risks Table:** Transaction_ID, Risk_Incident, Risk_Type, Incident_Severity, Error_Code  
- **System Behavior Table:** User_ID, System_Latency, Login_Frequency, Failed_Attempts, IP_Region    

The data is designed to replicate real-world accounting system operations and risk events, making it suitable for research in **financial risk management, fraud detection, and AI-driven decision support**.

---

## Folder Structure
```
powerbi-financial-transactions-risk-analysis/
│
├── data/
│ ├── transactions.csv
│ ├── risks.csv
│ ├── system_behavior.csv
│
├── report/
│ └── analysis_report.pdf
│
├── dashboard/
│ └── Financial_Transaction_Risk_Analysis.pbix
│
└── README.md
```

---

## KPIs & Measures

### Transactions
- **Total Transactions:** 10,000  
- **Total Amount:** 49.89M  
- **Average Transaction Value:** 4.99k  
- **Visualizations:** Transactions by Type, Currency Mix, Amount by Category, Top Counterparties  
- **Slicers:** Category, Transaction Type, Year  

### Risks & Incidents
- **Total Risk Incidents:** 1,448  
- **High Severity Incidents:** 471  
- **Visualizations:** Incidents by Risk Type, Risk Incident Count, Incidents by Counterparty  
- **Slicers:** Risk Type, Incident Severity, Error Code  

### System & User Behavior
- **Average Latency:** 300.98 ms  
- **Average Login Frequency:** 5.49 logins  
- **Average Failed Attempts:** 2.49  
- **Visualizations:** IP Regions Map, Latency vs Failed Attempts Scatter, Failed Attempts by User Line + Clustered Column  
- **Slicers:** Year, IP Region, User ID  

---

## Insights
- **Transactions:** High-value transactions and frequent transaction types highlight core operations. Top counterparties show key client relationships.  
- **Risks:** 471 high-severity incidents emphasize critical risk areas. Risk type and severity distribution helps target mitigation strategies.  
- **System Behavior:** Average latency and failed login attempts reveal system performance and security trends. Correlations between latency and failed attempts indicate potential optimization areas.  

---

## How to Use
1. Open the `.pbix` file in **Power BI Desktop**.  
2. Load the CSV files from the `data/` folder.  
3. Interact with the **dashboard**, use slicers to filter by category, type, severity, or year.  
4. Export visuals or full report as PDF for sharing or portfolio purposes.
