# Sales-Performance-Analysis
Leveraging Power BI Analytics To Analyse Sale's Performance And Create An Interactive Dashboard That Tracks Core Business KPIs

---

![image](https://github.com/user-attachments/assets/11427ff2-918a-4245-bf37-5fa20e6b94f7)

---

Introduction
Adventure Works is a global manufacturing leader in cycling equipment, catering to a wide array of customer segments across regions. 
This project utilizes Power BI to unlock strategic insights from the company’s sales data, build efficient and scalable data models, and deliver intuitive dashboards that empower leadership with data-backed decision-making tools. The findings recommend focusing on top products, reducing returns and engaging high-value customers.

---

Aim of the Analysis
•	Design a centralized, interactive Power BI dashboard that tracks core business KPIs.
•	Enable regional and product-level performance comparison.
•	Identify high-value customers and understand their behavior.
•	Deliver actionable insights to support sales optimization and strategic planning.

---

Data Preparation & Modeling
1 Data Connection and Transformation
Using Power BI Desktop, I imported and cleaned sales, product, and customer data. Key transformations included:
•	Data type standardization (dates, currency, numeric types).
•	Removal of null and duplicate records.
•	Extracted date components (Month, Year) using Power Query for time-series visuals.

2	Relational Data Model
The data modelling for this project follows a star schema approach, with a central Sales and Return Fact Table and linked dimension tables (Product, Customer, Calendar, territory). Relationships were created using primary/foreign keys, enabling accurate aggregations and filtering across visuals.

 ![image](https://github.com/user-attachments/assets/787c408a-737f-47af-b913-eedaa0c7e709)

---

Dashboard Visualization 
The final Power BI report was structured into four thematic dashboards: Executive Overview, Map, Customer Insights and Product Analysis.
**Executive Dashboard**
Total Revenue increased by 212.14% between January 2020 and June 2022, with the steepest growth (127.18% / $1.02M) occurring between August 2021 and June 2022.
Among product categories, Accessories led in Total Orders (16,983)—143.45% higher than Clothing (6,976)—followed by Bikes (13,929).

![image](https://github.com/user-attachments/assets/bf4440a5-89ce-4d05-ad63-4db63bf9fcc3)

---

Regionally, the United States had the highest Total Orders (8,700), nearly 280% more than Germany (2,294), the lowest.

![image](https://github.com/user-attachments/assets/bee7f92e-d0c9-4203-a80f-fe20c1daa7a4)

---

Customer Dashboard
Revenue per Customer declined 72.48% from January 2020 to June 2022 but rebounded 61% (£332) starting August 2021. Customers in the Average Income group made the most orders (11,600), followed by Low (10,266) and High (2,827). Professionals contributed the most to order volumes.
 
---

![image](https://github.com/user-attachments/assets/ca0fbeaa-4b61-4f65-be6f-48886d357ffb)

---

Product Dashboard
Profitability trendlines showed steady improvement. Return rates were relatively low across top products, except for some helmets with >3% return rates. Adjusted Profit and Total Profit rose significantly (230.3% increase) between June 2021 and June 2022, with the steepest jump from 106.38 to 493.23 between June and August 2021. However, Orders declined for a 3-month period starting in August 2021.
 
![image](https://github.com/user-attachments/assets/da26413f-d14f-4ec2-9c0a-8ab87b22d267)

---

Recommendations
•	Improve Return Rates: Investigate causes behind high return rates for specific helmets and conduct quality checks or improve sizing/fit guidance for customers.
•	Leverage High-Value Customers: Create loyalty programs or targeted offers for top 100 customers. Use customer segment insights (e.g., professionals, income brackets) to inform campaigns.
•	Prioritize High-Growth Products & Categories: Invest in marketing top sellers like Accessories and high-margin items like the Water Bottle – 30 oz.
•	Focus on High-Performing Products: Explore bundling strategies for top-selling products to drive volume such as Helmets (especially Sport-100 Red/Blue).
•	Target Growth Windows: Capitalize on periods like August–June, when revenue and profit trends show steep growth.
•	Address Order Volatility: Analyze and stabilize order declines observed from August to November 2021.
•	Engage Core Customer Segments: Focus on Average and Low-income groups, which show highest order volumes, and create strategies to further improve Revenue per Customer.
•	Leverage Regional Leaders: Use insights from top-performing regions like the U.S. to inform strategies in underperforming markets such as Germany.
