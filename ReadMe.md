# ☕ Coffee Shop Sales & Financial Dashboard

## 📘 Project Overview
This project analyzes the **business performance of a coffee shop chain** through sales, product, and customer data.  
The objective is to provide a **comprehensive financial overview**, **evaluate product performance**, and **analyze customer behavior** to help the business optimize sales strategies and improve profitability.

---

## 🎯 Project Objectives
- Analyze **Revenue**, **Profit**, and **Profit Margin**.  
- Identify the **best-selling products** and **most profitable product lines**.  
- Evaluate the effectiveness of the **Loyalty Program**.  
- Track **monthly sales trends** and **growth rates (YoY, MoM)**.  
- Understand **customer behavior** by country and market segment.

---

## 🧩 Data Structure

### 1️⃣ `order` Table
| Column | Description |
|---------|--------------|
| Customer ID | Unique customer identifier |
| Product ID | Product code |
| Quantity | Quantity sold |
| Sales | Total sales (Quantity × Unit Price) |
| Coffee Type | Coffee type code (A, R, L, E) |
| Roast Type | Roast level (L, M, D) |
| Size | Package size (0.2kg – 2.5kg) |
| Country | Customer’s country |
| Loyalty Card | Loyalty program status (Yes/No) |

### 2️⃣ `customer` Table
| Column | Description |
|---------|--------------|
| Customer ID | Unique customer identifier |
| Customer Name | Customer’s name |
| Country | Customer’s country |
| Loyalty Card | Loyalty program status (Yes/No) |

### 3️⃣ `product` Table
| Column | Description |
|---------|--------------|
| Product ID | Product code |
| Coffee Type | Type of coffee |
| Roast Type | Roast level |
| Size | Package size |
| Unit Price | Selling price |
| Profit | Average profit per unit |

---

## 📊 Dashboard Overview

### 🏦 **Page 1 – Financial Overview**
**Goal:** Provide a financial summary of revenue, cost, and profit.  
**Main Components:**
- KPI Cards: Revenue, COGS, Profit, Profit Margin (%), YoY Growth (%)
- Line Chart: *YTD Sales by Month*
- Column Chart: *Monthly Revenue Growth (%)*
- Map Chart: *Revenue by Country*
- Table: *P&L Summary (Revenue – COGS – Profit)*

**💡 Key Insights:**
- Total Revenue: **$45.13K**, Gross Margin **10.02%**.  
- **USA** accounts for **78.96% of total revenue**, the main market.  
- **September** shows a **+74% revenue increase**, indicating strong seasonality.

---

### ☕ **Page 2 – Product Analysis**
**Goal:** Evaluate product performance and profitability.  
**Main Components:**
- Bar Chart: *Top 10 Best-Selling Products*
- Column Chart: *Profit Margin by Coffee Type*
- Donut Chart: *Sales by Roast Type*
- Column Chart: *Sales by Package Size*
- Table: *Product Details (ID, Type, Size, Sales, Profit, Margin)*

**💡 Key Insights:**
- **2.5kg packages** represent **52.7% of total revenue**.  
- **Light Roast** products generate the highest revenue share (38.45%).  
- **Liberica** shows the **highest profit margin (13%)**, suggesting expansion potential.

---

### 👥 **Page 3 – Customer Analysis**
**Goal:** Understand customer behavior and value.  
**Main Components:**
- KPI Cards: Total Customers, Avg Revenue per Customer, Loyalty Ratio (%)
- Donut Chart: *Loyalty vs Non-Loyalty Revenue*
- Bar Chart: *Top 10 Customers by Revenue*
- Line Chart: *Customer Retention Rate by Month*
- Map/Bar Chart: *Customers by Country*

**💡 Key Insights:**
- Total of **1,000 customers**, with **53.65% Loyalty members** generating over **50% of total revenue**.  
- **USA** is the dominant market (78%), followed by **Ireland (14%)**.  
- **Low retention rate** indicates room for improvement in customer engagement and promotions.

---

## 📈 Key Findings & Recommendations
- Identified the **most profitable product segment (Liberica – 2.5kg package)**.  
- **Loyalty Program** generates **>50% of total sales**, proving its effectiveness.  
- **September sales spike (+74%)** suggests strong seasonal impact – replicate this marketing approach.  
- Improve **customer retention** and expand into **Ireland and UK markets** for diversification.

---