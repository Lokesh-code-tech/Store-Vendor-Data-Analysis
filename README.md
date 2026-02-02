# 📦 Purchase & Sales Data Analysis  
### Vendor Performance, Store Profitability & Inventory Risk

## 📌 Project Overview
This project analyzes end-to-end retail transaction data to evaluate **vendor performance**, **store profitability**, and **inventory inefficiencies**.  
The data represents the flow of goods from **vendors to stores and then to customers**.

The objective of this analysis is to identify:
- High-performing and high-risk vendors
- Profitability patterns across stores
- Inventory inefficiencies such as deadstock
- Operational risks related to cost and lead time

The project is designed as a **portfolio project** and follows a realistic analytics workflow using **SQL, Python, and Power BI**.

---

## 🗂️ Data Description

The project uses **two CSV datasets**:

### 1️⃣ Purchase Data (Vendor → Store)
Represents inventory procurement by stores from vendors.
- Vendor Name / Vendor Number  
- Product details (Brand, Description, Size)  
- Purchase Quantity  
- Purchase Price  
- Total Purchase Amount  
- Dates: PO Date, Receiving Date, Invoice Date, Pay Date  

### 2️⃣ Sales Data (Store → Customer)
Represents sales transactions at store level.
- Store  
- Product details (Brand, Description, Size)  
- Sales Quantity  
- Sales Price  
- Sales Amount  
- Sales Date  

---

## 🔄 Data Pipeline

1. CSV files were loaded into a **relational database**
2. Data was extracted from the database using **SQL**
3. Extracted data was loaded into **Pandas DataFrames**
4. Data analysis and feature engineering were performed in **Python**
5. Final analytical outputs were visualized using **Power BI**

This pipeline mirrors a real-world data analytics workflow.

---

## 🎯 Analysis Performed

### 🏭 Vendor Analysis
- Top 20 vendors by **total sales**
- Top 20 vendors by **average lead time**
- Top 20 vendors contributing most to **store profit**
- Identification of **problematic vendors** based on:
  - High cost
  - Long lead time
  - Low profit contribution
  - High dependency

---

### 🏪 Store Analysis
- Relationship between **sales and profit** at store level
- Store-level profitability comparison
- Top 20 stores with the **highest deadstock**

---

### 📦 Inventory & Deadstock Analysis
- Deadstock identification using **purchase vs sales quantity**
- Top 20 brands with the **highest deadstock**
- Store-level deadstock exposure and risk identification

---

## 📊 Key Metrics Used
- Total Sales  
- Total Purchase Cost  
- Profit  
- Margin %  
- Average Lead Time  
- Deadstock Quantity  
- Sell-through Rate  

---

## 📈 Power BI Reporting
The Power BI report includes:
- Vendor performance dashboards
- Store profitability and efficiency analysis
- Sales vs profit relationship visualizations
- Deadstock analysis by store and brand
- Vendor and store risk identification tables

The dashboards are designed to support **business decision-making**.

---

## 🛠️ Tools & Technologies
- **Python** (Pandas, NumPy, Matplotlib)
- **SQL**
- **Jupyter Notebook**
- **Power BI**
- **DAX**
- **GitHub**
