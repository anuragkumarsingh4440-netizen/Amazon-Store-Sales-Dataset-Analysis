# 📊 Amazon Store Sales Analysis Dashboard  

## 📌 Project Overview  
This project focuses on analyzing Amazon store sales data and creating an **interactive Power BI dashboard**.  
The dataset was already in **clean and structured form**, so only **basic EDA and preprocessing** were done using Python before visualization in Power BI.  

The dashboard highlights **sales performance, profit trends, customer segments, product categories, and regional contributions**, helping businesses make data-driven decisions.  

---

## 🗂 Dataset  
- **Rows:** 5,901 transactions  
- **Columns:** 21 (Orders, Customers, Products, Sales, Profit, Returns, Payment, Geography)  
- **Source:** Provided Amazon Store Sales dataset (CSV/Excel format)  

---

## 🔎 Workflow  

### 1. Data Checks & Light EDA (Python)  
- Verified column types and converted date fields  
- Checked for missing values (none found)  
- Validated numerical ranges (Sales, Profit, Quantity)  
- Quick visualizations to confirm distributions  

### 2. Dashboard Development (Power BI)  
- Imported dataset into Power BI  
- Built **KPIs using DAX**:  
  - Total Sales  
  - Total Profit  
  - Average Order Value  
  - Return %  
- Designed **interactive visuals**:  
  - Sales by Region & State  
  - Profit by Category & Sub-Category  
  - Customer Segment Distribution  
  - Payment & Shipping Mode Trends  
- Added **filters & drilldowns** for dynamic exploration  

---

## 💡 Key Insights  
✔ **Consumer segment** contributes ~51% of sales  
✔ **California & New York** lead in total revenue  
✔ **Technology** products yield highest profit margins  
✔ **~5% orders returned** → impacts profitability  
✔ **Cash on Delivery (COD)** dominates payment methods  

---

## 🛠 Tech Stack  
- **Python (light EDA):** Pandas, Matplotlib, Seaborn  
- **Power BI:** DAX, Interactive Dashboard, Data Modeling  
- **Excel/CSV:** Data source  

---

## 📸 Dashboard Preview  
<img width="934" height="535" alt="image" src="https://github.com/user-attachments/assets/a577283e-fece-41fd-9856-9b5d452e0175" />

---

## 🚀 How to Use  
1. Clone this repository  
   ```bash
   git clone https://github.com/your-username/amazon-store-sales-dashboard.git
