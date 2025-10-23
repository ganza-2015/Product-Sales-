# 📊 Product Sales Data Analysis & Visualization 

![Image](https://github.com/user-attachments/assets/83be65c7-1875-4467-926f-c6b51943d31f)

## 🧩 Project Overview
The **Product Sales Data Analysis Project** explores over **200,000 sales records** to uncover performance trends, regional insights, and profitability patterns.  
Data was cleaned, analyzed, and visualized using **Microsoft Excel** and **Power BI**, enabling deeper business understanding and smarter decision-making.

---

## 🎯 Objectives
- Clean and transform the raw dataset for consistency.  
- Generate key metrics including **Revenue**, **Profit**, **Quantity**, and **Profit Margin**.  
- Identify top-performing **regions**, **categories**, and **customers**.  
- Visualize insights interactively using **Power BI dashboards**.

---

## 🧠 Tools & Technologies
| Tool | Purpose |
|------|----------|
| **Microsoft Excel** | Data preparation, pivot tables, and charting |
| **Power BI** | Dashboard creation and data visualization |
| **Statistics** | Descriptive analysis and trend detection |

---

# 📊 PSDD1 Business Data Analysis Project  
### **Excel | Power BI | Python | Data Visualization | Statistics**  
By **Olori Ajie**

---

## 📁 Project Overview  

This project analyzes business performance using the **PSDD1 dataset**.  
The goal is to uncover insights about **sales performance**, **product profitability**, **customer contributions**, and **regional trends** using **Excel**, **Python**, and **Power BI**.

---

## 🎯 Business Questions  

1. 🏆 **Which region generates the highest revenue?**  
2. 💰 **What are the top 10 most profitable products?**  
3. 🗺️ **Are some product categories more popular in certain regions?**  
4. 👥 **Which customers contribute the most to total revenue?**

---

## 🧾 Dataset Information  

| Column Name | Description |
|--------------|-------------|
| **Order_Date** | Transaction date |
| **Region** | Sales region |
| **Category** | Product category |
| **Sub_Category** | Product sub-category |
| **Product_Name** | Product name |
| **Customer_Name** | Customer name |
| **Quantity** | Units sold |
| **Revenue** | Total sales value |
| **Profit** | Profit earned from each sale |

---

## 🧠 Analysis Approach  

The analysis was performed using **Python (pandas)** and visualized in **Power BI** for better insight presentation.  

### ✅ Step 1 — Load and Clean Data  
```python
import pandas as pd

# Load dataset
df = pd.read_excel("PSDD1.xlsx", sheet_name="Dataset")

# Clean column names
df.columns = df.columns.str.strip()


## 📈 Key Insights
- **Total Revenue:** ₦4.27 Billion (approx.)  
- **Total Profit:** ₦1.39 Billion (approx.)  
- **Total Quantity Sold:** 1.2 Million units (approx.)  
- **Overall Profit Margin:** ~32.6%  

### 🔹 Top 5 Regions by Revenue
1. **South Region** — Highest revenue and profit margin  
2. **West Region** — Strong sales volume  
3. **East Region** — Moderate growth with balanced profitability  
4. **Centre Region** — Consistent sales performance  
5. **North Region** — Developing potential

### 🔹 Top 5 Categories by Profit
- Technology  
- Office Supplies  
- Home & Furniture  
- Appliances  
- Art & Stationery  

### 🔹 Top Customers by Revenue
- Robert Barnes  
- Mercedes Arias  
- Jacob Wilson  
- Monique Kim  
- Jeffrey Smith  

---



