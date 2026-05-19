# restaurant-analysis
**Scalable data analysis project using **Databricks**, **SQL**, and **Power BI** to transform **11M+** records into actionable business insights and real-time dashboards.**
The data was originally distributed across multiple sources:
7 CSV files
2 JSON files

---

⚙️ Data Integration (Databricks + SQL)
1️⃣ Merging CSV Files
The first step was combining the 7 CSV files into a single structured table using SQL:
This step ensured all tabular data was unified into one dataset (restaurants_data1).

<img width="422" height="391" alt="image" src="https://github.com/user-attachments/assets/490fccef-d1cd-40e2-86a1-c447b8c8c06e" />








2️⃣ Merging JSON Files
Next, the two JSON files were combined into a single table:
sandbox:/mnt/data/image.png
This created a second dataset (restaurants_data2) containing semi-structured data.

<img width="427" height="140" alt="image" src="https://github.com/user-attachments/assets/d67f7583-fb15-423a-a1a3-e0e813b1479f" />






3️⃣ Combining All Data Sources
Finally, both datasets were merged together to create one unified dataset.

<img width="335" height="137" alt="image" src="https://github.com/user-attachments/assets/9a9cdcfc-4e65-431b-9957-c621cb9c253b" />

---


🛠️ Data Workflow

Engineered additional features like Year & Month columns for better time-based analysis.

<img width="311" height="197" alt="image" src="https://github.com/user-attachments/assets/f5cb4517-2f21-44ea-bfa5-c6ea0382b2b1" />





Connected data to Power BI using DirectQuery to ensure real-time performance and scalability.

Applied transformations in Power Query.

<img width="600" height="231" alt="image" src="https://github.com/user-attachments/assets/506b8628-f94f-4b54-b9c9-3c5427a6a481" />



---

📊 Key Metrics Built

Total Revenue
Total Orders
Average Order Value (AOV)
Average Rating
Average Revenue
Percentage-based KPIs for deeper insights.
Additional measures were created to enhance analysis and provide deeper insights.

<img width="275" height="563" alt="image" src="https://github.com/user-attachments/assets/b177dc25-ec6a-4e4c-a7d3-5341a527e018" />



---

🔥 Most Important Insight
Revenue is highly concentrated in a few key drivers.

- Top 5 items generate **55.81%** of total revenue.
  
<img width="652" height="300" alt="image" src="https://github.com/user-attachments/assets/d1bbe9d8-371f-47af-be4b-64e6922afec7" />




- Grills category contributes **34.89%**.
  
<img width="500" height="328" alt="image" src="https://github.com/user-attachments/assets/2c1efe57-e351-4aba-9e15-c5c7fd42ef92" />




- Cairo branch alone drives **34.99%**.
  
<img width="587" height="302" alt="image" src="https://github.com/user-attachments/assets/f7b3b33d-4fa0-4cd9-9cdb-d6ee26b2746f" />



---

📌 Business Impact

- Identified high-dependency revenue areas
- Highlighted scaling opportunities for top-performing items and branches
- Enabled faster decision-making using real-time dashboards

---


🚀 Final Thoughts

This project is a practical example of how large, fragmented datasets can be transformed into actionable insights using modern data tools.

By identifying revenue concentration and key performance drivers, this analysis provides a strong foundation for strategic decisions, optimization, and business growth.


You can get the data from this link:  https://drive.google.com/drive/folders/1KcGAxBpvXuYHrVnfz6KaxJszFzalE5pP?usp=drive_link
