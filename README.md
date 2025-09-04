# Sales Performance 2023 VS 2024

##  Project Overview
This project analyzes a sales dataset to gain insights into **revenue distribution, regional sales trends, and product performance**.  
The analysis compares **2023 vs 2024 monthly sales**, evaluates **regional performance**, and provides a **product-wise breakdown** of sales, cost, quantity, and profit.  

The goal is to help decision-makers understand market behavior, optimize resources, and identify growth opportunities.

---

##  Dataset Sources & Description
- **Source:** Sales Dataset (Excel format)  
- **Sheet Used:** `Sheet1`  
- **Rows:** 300  
- **Columns:** 10  

| Column | Description |
|--------|-------------|
| OrderID | Unique order identifier |
| Date | Order transaction date |
| Month | Month of order |
| Year | Year of order |
| Product | Product name |
| Category | Product category (e.g., Electronics, Accessories) |
| Region | Region of sales (e.g., East, West, South, North) |
| Sales | Sales value ($) |
| Quantity | Number of items sold |
| Cost | Total cost ($) |

---

##  Objectives
- Compare **monthly sales distribution for 2023 vs 2024**  
- Analyze **regional sales trends**  
- Provide a **product-level breakdown** of sales, cost, quantity, and profit  
- Generate **dashboards** for quick monitoring  
- Highlight **key insights and recommendations** for business growth  

---

##  Tools Used
- **Microsoft Excel** – Data cleaning, transformation, analysis  
- **Power Query** – Data preparation & processing  
- **DAX (Data Analysis Expressions)** – Deriving KPIs and measures  
- **Pivot Tables & Charts** – Visualization & dashboards  

---

##  Data Preparation & Cleaning
1. Imported the dataset into Excel  
2. Verified column consistency and removed missing values  
3. Created a **Profit column** = `Sales - Cost`  
4. Standardized product and region categories  
5. Used Power Query for transformations and aggregations  

---

##  Exploratory Data Analysis
- Checked **total sales distribution** across years  
- Analyzed **regional contribution** to total sales  
- Reviewed **product performance** based on sales, cost, and profit  
- Identified **seasonality patterns** in monthly sales  

---

##  Data Analysis & Market Insights

### 1.  Monthly Revenue Distribution (2023 vs 2024)
- 2023 showed **steady revenue growth in Q4 (Oct–Dec)** due to higher seasonal demand.  
- 2024 reflected **stronger mid-year sales (Jun–Aug)** with increased electronics sales.  
- Revenue in 2024 overall surpassed 2023, highlighting **year-on-year growth**.

### 2.  Regional Sales Distribution
- **East & West regions** contributed the highest sales share.  
- **South region** saw consistent but lower revenue.  
- **North region** showed growth opportunities but underperformed compared to others.  

### 3.  Product-wise Breakdown
- **High-revenue products:** Printers, Monitors, and Laptops (Electronics dominate).  
- **Accessories (Mouse, Keyboards, etc.)** generated smaller sales but higher **quantity sold**, showing volume-based demand.  
- Profit margins were **highest in electronics**, while accessories offered lower per-unit profit.  

### 4.  Sales, Cost, Quantity & Profit
- **Total Sales:** Aggregated across 2023–2024  
- **Total Cost:** Captured from cost column  
- **Profit:** Derived as `(Sales – Cost)`  
- **Quantity Trend:** Accessories sold in large numbers, while electronics had fewer but higher-value sales  

---

##  Dashboards
Interactive dashboards were built in **Excel** featuring:
1. **Monthly Revenue (2023 vs 2024)**  
2. **Regional Sales Contribution**  
3. **Category & Product-Wise Performance**  
4. **Profitability Analysis**  
5. **Quantity vs Revenue Correlation**  

<img width="1817" height="843" alt="Sales Performance" src="https://github.com/user-attachments/assets/9de23e53-83bc-44fd-9419-4c64324a41fe" />
---

##  Key Findings
1. **2024 outperformed 2023** in terms of revenue and profit.  
2. Electronics are the **primary revenue driver**.  
3. Accessories provide **volume sales** but lower profit margins.  
4. **East and West regions** dominate sales, while **North region** needs market expansion.  
5. Seasonal trends show **Q4 and mid-year peaks**.  

---

##  Recommendations
- Increase **marketing investment** in North region to boost sales.  
- Expand **electronics product line** as it drives most revenue.  
- Leverage accessories for **bundle sales strategies** to improve profitability.  
- Monitor **seasonal trends** and allocate stock strategically in peak months.  

---

##  Limitations
- Dataset covers only **2023–2024 period** (short-term insights).  
- No customer-level details for deeper segmentation.  
- Does not account for **external market factors** (inflation, competition, etc.).  

---

##  Conclusion
The analysis highlights that **2024 achieved stronger revenue and profitability compared to 2023**, with **electronics leading sales and profit margins**. Regional analysis revealed **East & West dominance**, but opportunities remain for the **North region**.  
By aligning strategy with these insights, businesses can **drive growth, optimize resources, and improve profitability**.  

---

## 📚 References
- Dataset: *Sales Dataset (Excel)*  
- Tools: *Microsoft Excel, Power Query, DAX*  
- Concepts: *Sales Analysis, Revenue Trends, Profitability Analysis*  
.
