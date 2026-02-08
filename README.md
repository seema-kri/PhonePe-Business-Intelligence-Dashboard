# 📊 PhonePe Business Intelligence Dashboard
### End-to-End Transaction Analytics & Failure Monitoring Using Power BI

---

## 🚀 Project Overview

The **PhonePe Business Intelligence Dashboard** is an end-to-end real-world data analytics project built using Power BI. This dashboard analyzes large-scale digital payment transactions to monitor service performance, identify failed payment patterns, and provide actionable business insights.

This project simulates the responsibilities of a Data Analyst working in a fintech organization like PhonePe, focusing on improving transaction reliability and customer experience through data-driven decision-making.

The dashboard processes and visualizes **300,000+ transaction records** across multiple PhonePe services.

---

## 🎯 Project Objective

The primary objective of this project is to build an interactive and centralized reporting dashboard that enables stakeholders to:

- Monitor overall transaction performance
- Identify root causes of failed payments
- Compare performance across different PhonePe services
- Track monthly transaction growth trends
- Support strategic business decision-making

---

## 🧠 Business Problem Statement

Digital payment platforms process millions of transactions daily. High failure rates can lead to:

- Customer dissatisfaction  
- Reduced platform usage  
- Revenue loss  
- Poor user experience  

This dashboard helps business teams quickly identify failure causes and detect underperforming services, enabling proactive operational improvements.

---

## 📂 Dataset Information

### 📌 Dataset Size
- Approximately **300,000+ transaction records**

### 📌 Data Source
- Microsoft Excel

### 📌 Data Sheets Used
- All Users  
- All Transactions  

### 📌 Key Columns

- Transaction ID  
- User ID  
- Service Type  
- Sub-Service Category  
- Transaction Amount  
- Payment Status  
- Failure Reason  
- Transaction Date  
- User Demographics  

---

## 📥 Dataset Availability

Due to GitHub file size limitations, the complete dataset cannot be uploaded to this repository.

### ✅ Full Dataset Access
The full dataset used to build this dashboard is available below:

🔗 **Full Dataset Download:**  
https://docs.google.com/spreadsheets/d/1naFpiwVuwC84gq43W7nLGt8buEIaCamy/edit?usp=drive_link&ouid=113413939000598330207&rtpof=true&sd=true
---

## 📊 Dashboard Access

Due to Power BI publishing limitations, the complete dashboard is shared via OneDrive.

🔗 Power BI Dashboard File (PBIX):
https://1drv.ms/u/c/e8692590cf0392b3/IQDfmPBM-PtSR41JCFvoH7vhARLw661WgOXQ8hTlF6Bsj7Y?e=idSRuF

The file can be downloaded and opened using Power BI Desktop.

## 🏗️ Dashboard Structure

The dashboard contains **5 interactive report pages**.

---

### 🏠 Homepage – Executive Summary

Provides a high-level overview of platform performance:

- Total Transaction Amount  
- Total Transactions  
- Successful Payments  
- Failed Payments  
- Service Contribution Analysis  
- Global Date Range Filter  

---

### 🛡️ Insurance Services Analytics

Analyzes premium payments across:

- Term Life Insurance  
- Health Insurance  
- Vehicle Insurance  

Key Visuals:
- Monthly Amount Trends  
- Payment Success Rate  
- Service Performance Comparison  

---

### 💰 Loan Services Dashboard

Analyzes loan-related services including:

- Gold Loans  
- Auto Loans  
- Mutual Fund Investments  
- Credit Score Services  

Key Visuals:
- Loan Type Contribution  
- Monthly Loan Growth Trends  

---

### 📱 Money Transfer Analytics

Tracks transaction channels such as:

- UPI ID Transfers  
- Mobile Number Transfers  
- QR Code Payments  
- Self Account Transfers  

Key Insights:
- Channel Usage Distribution  
- Transaction Performance Comparison  

---

### 🔌 Recharge & Bills Dashboard

Monitors utility payments including:

- Mobile Recharge  
- DTH Payments  
- Fastag Recharge  
- Cable TV Bills  

Key Visuals:
- Seasonal Payment Trends  
- Service Contribution Analysis  

---

## 📊 Key Performance Indicators (KPIs)

The dashboard tracks critical business metrics including:

- Total Transaction Amount  
- Total Number of Transactions  
- Successful Transactions  
- Failed Transactions  
- Failure Rate Percentage  
- Monthly Growth Trends  

---

## ❌ Failed Payment Analysis

### Failure Reasons Identified

- Server Errors  
- Wrong PIN  
- Insufficient Balance  
- Bank Declined  
- Incorrect Payment Details  

### 📈 Key Business Insight

Server-related failures contributed significantly during peak transaction periods, suggesting backend infrastructure scalability challenges rather than user errors.

---

## ⚙️ Tools & Technologies Used

| Tool | Purpose |
|-------|-----------|
| Power BI | Dashboard Development |
| Power Query | Data Cleaning & Transformation |
| DAX | KPI and Measure Creation |
| Microsoft Excel | Data Source |
| GitHub | Documentation & Version Control |

---

## 🧮 Sample DAX Measures

### Total Transaction Amount
```DAX
Total Amount = SUM(Transactions[Amount])
```

### Total Transactions
```DAX
Total Transactions = COUNT(Transactions[Transaction ID])
```

### Failed Payments
```DAX
Failed Payments =
CALCULATE(
    COUNT(Transactions[Transaction ID]),
    Transactions[Payment Status] = "Failed"
)
```

---

## 📈 Business Impact & Outcomes

This dashboard enables stakeholders to:

✅ Detect high-risk transaction failure causes  
✅ Monitor service-level performance  
✅ Track platform transaction health  
✅ Improve operational monitoring  
✅ Support real-time decision making  
✅ Enhance customer satisfaction strategy  

---

## 📌 Project Features

✔ Multi-page interactive dashboard  
✔ Service-level analytics  
✔ Failure root cause detection  
✔ Monthly trend analysis  
✔ Dynamic slicers & filters  
✔ Business-focused storytelling visuals  

---

## 🔮 Future Enhancements

- Real-time data integration  
- Predictive payment failure analysis using Machine Learning  
- Regional transaction performance analysis  
- Customer segmentation insights  

---

## 👩‍💻 Author

**Seema Kumari**  
B.Tech Student | Aspiring Data Analyst  
NIT Agartala  

### Skills
- Power BI  
- SQL  
- Excel  
- Python  
- Data Visualization  
- Business Analytics  

---

## ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub.
