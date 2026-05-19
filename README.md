
# 🍽️ Restaurant Data Analysis & Business Insights

> End-to-end scalable data analysis project using Databricks, SQL, and Power BI to transform 11M+ records into actionable insights and real-time dashboards for business decision-making.

![Tool](https://img.shields.io/badge/Tool-Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Platform](https://img.shields.io/badge/Platform-Databricks-E25A1C?style=flat-square&logo=databricks&logoColor=white)
![Language](https://img.shields.io/badge/Language-SQL%20%7C%20DAX-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-2ea44f?style=flat-square)
![Data](https://img.shields.io/badge/Data-11M%2B%20Rows-blueviolet?style=flat-square)
---

## 📌 Table of Contents

- [⚙️ Data Engineering (Databricks)](#️-data-engineering-databricks)
- [📊 Data Visualization (Power BI)](#-data-visualization-power-bi)
- [📈 Key Metrics](#-key-metrics)
- [🔥 Key Insights](#-key-insights)
- [🚀 Business Impact](#-business-impact)
- [🛠️ Tools & Technologies](#️-tools--technologies)
- [🚀 Final Thoughts](#-final-thoughts)
- [Data Source](#-data-source)

---

## ⚙️ Data Engineering (Databricks)

The raw dataset was distributed across:

- 7 CSV files  
- 2 JSON files  

### 🔧 Steps:

1. **Merging Structured Data (CSV)**  
   Combined multiple CSV files into a unified dataset using SQL.
<img width="422" height="391" alt="image" src="https://github.com/user-attachments/assets/490fccef-d1cd-40e2-86a1-c447b8c8c06e" />


2. **Merging Semi-Structured Data (JSON)**  
   Processed and structured JSON files into analyzable tables.
<img width="427" height="140" alt="image" src="https://github.com/user-attachments/assets/d67f7583-fb15-423a-a1a3-e0e813b1479f" />


3. **Final Integration**  
   Joined all datasets into a single clean dataset ready for analysis.
<img width="335" height="137" alt="image" src="https://github.com/user-attachments/assets/9a9cdcfc-4e65-431b-9957-c621cb9c253b" />


4. **Feature Engineering**  
   Created additional columns such as **Year & Month** for time-series analysis.
<img width="311" height="197" alt="image" src="https://github.com/user-attachments/assets/f5cb4517-2f21-44ea-bfa5-c6ea0382b2b1" />

---

## 📊 Data Visualization (Power BI)

- Connected data using **DirectQuery** for real-time performance  
- Applied transformations using **Power Query**.
<img width="600" height="231" alt="image" src="https://github.com/user-attachments/assets/506b8628-f94f-4b54-b9c9-3c5427a6a481" />
 
- Built interactive dashboards across:

### 📌 Pages:

- Executive Summary.
<img width="1127" height="635" alt="image" src="https://github.com/user-attachments/assets/3f69959e-84ec-4d4d-b5d6-7e52c768117a" />
  
- Revenue Analysis.
<img width="1122" height="636" alt="image" src="https://github.com/user-attachments/assets/2f5a4536-47bd-4c42-bad5-b0ecf6421c24" />
  
- Customers & Items Analysis.
<img width="1121" height="633" alt="image" src="https://github.com/user-attachments/assets/1cda37a4-e15d-48f8-9eed-13e549199dd8" />
  

---

## 📈 Key Metrics

- 💰 Total Revenue  
- 🧾 Total Orders  
- 📊 Average Order Value (AOV)  
- ⭐ Average Rating  
- 📉 Average Revenue  
- 📊 Percentage-based KPIs.
    
<img width="275" height="563" alt="image" src="https://github.com/user-attachments/assets/b177dc25-ec6a-4e4c-a7d3-5341a527e018" />

---

## 🔥 Key Insights

> 📌 Revenue is highly concentrated across a few key drivers:

- Top 5 items generate **55.81%** of total revenue.
  
<img width="652" height="300" alt="image" src="https://github.com/user-attachments/assets/d1bbe9d8-371f-47af-be4b-64e6922afec7" />




- Grills category contributes **34.89%**.
  
<img width="500" height="328" alt="image" src="https://github.com/user-attachments/assets/2c1efe57-e351-4aba-9e15-c5c7fd42ef92" />




- Cairo branch alone drives **34.99%**.
  
<img width="587" height="302" alt="image" src="https://github.com/user-attachments/assets/f7b3b33d-4fa0-4cd9-9cdb-d6ee26b2746f" />

---
### Additional Insights:

- 📅 Clear **seasonality patterns** across months  
- 💳 Around **50% of transactions are cash-based**  
- 🍽️ Balanced split between dine-in, delivery, and takeaway  
- 📊 Noticeable variation in customer spending (AOV)

---

## 🚀 Business Impact

- Identified **high-dependency revenue areas**  
- Highlighted **scaling opportunities** for key products and branches  
- Enabled **real-time decision-making** using DirectQuery  
- Improved visibility into **customer behavior and trends**

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| Power BI | Dashboard design, DAX, visualization |
| Databricks | Data processing and transformation |
| SQL | Data integration and cleaning |
| Power Query | Data transformation |
| DirectQuery | Real-time analytics |

---

## 🚀 Final Thoughts

This project demonstrates how large-scale raw data can be transformed into meaningful insights using modern data tools.

By identifying key revenue drivers and behavioral patterns, the analysis supports better decision-making, operational optimization, and business growth.

## Data Source 
You can get the data from this link:  https://drive.google.com/drive/folders/1KcGAxBpvXuYHrVnfz6KaxJszFzalE5pP?usp=drive_link
