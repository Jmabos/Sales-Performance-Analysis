# 📊 Sales Performance Analysis

**Leveraging Power BI to Analyze Sales Performance and Build an Interactive Dashboard That Tracks Core Business KPIs**

---

![Sales Dashboard Cover](https://github.com/user-attachments/assets/11427ff2-918a-4245-bf37-5fa20e6b94f7)

---

## 🏢 Introduction

Adventure Works is a global manufacturing leader in cycling equipment, catering to a wide array of customer segments across regions.

This project utilizes Power BI to unlock strategic insights from the company’s sales data, build efficient and scalable data models, and deliver intuitive dashboards that empower leadership with data-backed decision-making tools. The findings recommend focusing on top products, reducing returns, and engaging high-value customers.

---

## 🎯 Aim of the Analysis

- Design a centralized, interactive Power BI dashboard that tracks core business KPIs  
- Enable regional and product-level performance comparison  
- Identify high-value customers and understand their behavior  
- Deliver actionable insights to support sales optimization and strategic planning  

---

## 🧹 Data Preparation & Modeling

### 1. Data Connection and Transformation
Using Power BI Desktop, I imported and cleaned sales, product, and customer data. Key transformations included:

- Standardized data types (dates, currency, numeric types)  
- Removed null and duplicate records  
- Extracted date components (Month, Year) using Power Query for time-series visuals  

### 2. Relational Data Model  
The model follows a **star schema** approach with:

- A central Sales and Return Fact Table  
- Dimension tables: Product, Customer, Calendar, Territory  
- Relationships created via primary/foreign keys for accurate aggregations and filtering  

![Data Model](https://github.com/user-attachments/assets/787c408a-737f-47af-b913-eedaa0c7e709)

---

## 📈 Dashboard Visualizations

The Power BI report is structured into **four thematic dashboards**:  
**Executive Overview**, **Map**, **Customer Insights**, and **Product Analysis**

### 🔹 Executive Dashboard
- Total Revenue increased by **212.14%** between Jan 2020 and Jun 2022  
- Steepest growth: **127.18% ($1.02M)** between Aug 2021 and Jun 2022  
- **Accessories** led in Total Orders (16,983), followed by **Bikes** (13,929) and **Clothing** (6,976)  

![Executive Dashboard](https://github.com/user-attachments/assets/bf4440a5-89ce-4d05-ad63-4db63bf9fcc3)

### 🌍 Regional Performance
- **United States**: Highest Total Orders (8,700), nearly **280% more** than Germany (2,294)

![Regional Map](https://github.com/user-attachments/assets/bee7f92e-d0c9-4203-a80f-fe20c1daa7a4)

---

### 👥 Customer Dashboard
- Revenue per Customer declined **72.48%** from Jan 2020 to Jun 2022, rebounded **61% (£332)** since Aug 2021  
- Average income group made most orders (11,600), followed by Low (10,266) and High (2,827)  
- **Professionals** made the highest volume of orders  

![Customer Insights](https://github.com/user-attachments/assets/ca0fbeaa-4b61-4f65-be6f-48886d357ffb)

---

### 📦 Product Dashboard
- **Profitability trendlines** showed strong upward growth  
- **Return rates** mostly low, except for helmets with >3%  
- **230.3% profit increase** between Jun 2021 and Jun 2022  
- Temporary decline in orders from Aug–Nov 2021  

![Product Analysis](https://github.com/user-attachments/assets/da26413f-d14f-4ec2-9c0a-8ab87b22d267)

---

## ✅ Recommendations

- **Improve Return Rates**  
  Investigate causes behind helmet returns; enhance sizing and quality control

- **Leverage High-Value Customers**  
  Create loyalty programs for top 100 customers using income and profession insights

- **Prioritize High-Growth Products**  
  Invest in marketing top sellers like Accessories and high-margin products (e.g., Water Bottle – 30 oz.)

- **Bundle Top Products**  
  Explore bundling strategies for top-selling items like Sport-100 Helmets

- **Capitalize on Growth Periods**  
  Focus marketing and sales initiatives between August–June, where revenue spikes

- **Address Order Volatility**  
  Stabilize order declines observed from Aug–Nov 2021 through promotional tactics

- **Engage Core Customer Segments**  
  Target Average and Low-income customers with tailored offers to improve revenue per customer

- **Replicate Regional Success**  
  Use insights from top-performing regions like the U.S. to boost performance in underperformers like Germany

---

🛠 Built with **Power BI**, **Power Query**, **DAX**, and solid **Data Modeling Principles**
