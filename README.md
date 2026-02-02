📌 Project Overview

This project focuses on analyzing end-to-end retail transaction data, covering the flow of goods from vendors to stores and finally to customers.
The objective is to evaluate vendor performance, store profitability, and inventory inefficiencies using real-world purchase and sales data.

The analysis aims to answer key business questions such as:

Which vendors contribute most to sales and profit?

Which vendors pose operational risks due to high cost or long lead times?

How do sales and profit relate at the store level?

Which stores and brands are accumulating deadstock?

The project combines SQL, Python (Pandas), and Power BI to simulate a real analytics workflow commonly used in retail and supply chain environments.

🗂️ Data Description

The project uses two CSV datasets:

1️⃣ Purchase Data (Vendor → Store)

Represents inventory procurement by stores from vendors.

Vendor Name / Vendor Number

Product details (Brand, Description, Size)

Purchase Quantity

Purchase Price

Total Purchase Amount

Dates: PO Date, Receiving Date, Invoice Date, Pay Date

2️⃣ Sales Data (Store → Customer)

Represents sales transactions at store level.

Store

Product details (Brand, Description, Size)

Sales Quantity

Sales Price

Sales Amount

Sales Date

🔄 Data Pipeline

CSV files were loaded into a relational database

Data was queried from the database

Data was then loaded into Pandas DataFrames

All analysis and feature engineering were performed using Python

Final analytical tables were visualized using Power BI

This approach mirrors a real-world data engineering + analytics workflow.

🎯 Key Analyses Performed
🏭 Vendor Analysis

Top 20 vendors by total sales value

Top 20 vendors by average lead time

Top 20 vendors contributing most to store profit

Identification of problematic vendors based on:

High cost

Long lead time

Low profit contribution

High dependency

🏪 Store Analysis

Relationship between sales and profit at store level

Store-level profitability comparison

Top 20 stores with the highest deadstock

Store performance benchmarking

📦 Inventory & Deadstock Analysis

Deadstock identification using:

Purchase Quantity vs Sales Quantity

Top 20 brands with the highest deadstock

Store-level deadstock exposure

Inventory risk identification

📊 Key Metrics & Concepts Used

Total Sales

Total Purchase Cost

Profit & Margin %

Average Vendor Lead Time

Deadstock Quantity

Sell-through Rate

Vendor & Store Risk Flags
