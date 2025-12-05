# E-Commerce-Sales-Analytics
End-to-end E-Commerce Sales Dashboard using Excel, SQL, and Power BI.
# 📊 E-Commerce Sales Analytics Dashboard

## 🔍 Project Overview
This project analyzes e-commerce sales data using **Excel, SQL, and Power BI** to generate business insights on sales performance, customer behavior, and product trends. It includes a 2-page interactive dashboard:

- **Sales Overview Dashboard**
- **Customer Insights Dashboard**

---

## 🛠 Tools Used
- **Excel** – Data cleaning & preparation  
- **SQL (MySQL)** – Data analysis (joins, aggregations, window functions)  
- **Power BI** – Dashboard design, DAX measures, KPIs  

---

## 📁 Project Files
- `Ecommerce_Analytics.pbix` – Power BI Dashboard  
- `ecommerce_data.csv` – Dataset  
- `sql_queries.sql` – SQL queries used in analysis  
- `README.md` – Project documentation  

---

## 📌 Key Insights
- Identified top-performing categories and products  
- Analyzed monthly revenue trends  
- Found high-value customers based on sales, orders, and quantity  
- Created KPIs such as Total Sales, Total Orders, AOV, Customer Sales, Customer Orders  

---

## 📊 Dashboard Pages
### 1️⃣ Sales Overview Dashboard
- Total Sales  
- Total Orders  
- Average Order Value (AOV)  
- Sales by Category  
- Sales by Product  
- Monthly Sales Trend  

### 2️⃣ Customer Insights Dashboard
- Customer Sales  
- Customer Quantity  
- Customer Orders  
- Top Customers  
- Customer Order Frequency  
- Customer Purchase Quantity  

---

## 📈 DAX Measures Used
```DAX
Total Amount = E_COMMERCE[Quantity] * E_COMMERCE[Price]
Total Sales = SUM(E_COMMERCE[Total Amount])
Total Orders = COUNT(E_COMMERCE[OrderID])
AOV = DIVIDE([Total Sales], [Total Orders])
Customer Sales = SUM(E_COMMERCE[Total Amount])
Customer Quantity = SUM(E_COMMERCE[Quantity])
Customer Orders = COUNT(E_COMMERCE[OrderID])

📬 Contact

Shashank Karma
Email: karmashashank112@gmail.com
Phone: 7610750013
