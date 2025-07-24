# 📊 E-Commerce Sales Comparison Dashboard (2009–2011)

This project presents a comprehensive Power BI dashboard comparing e-commerce sales between the fiscal years 2009–2010 and 2010–2011. It offers interactive visualizations to help identify patterns in product performance, seasonal trends, customer distribution, and revenue growth.

---

## 📌 Objective

To analyze and compare yearly performance of an e-commerce business using interactive visualizations and KPIs that provide valuable business insights.

---

## 🛠️ Tools Used

- Microsoft Power BI  
- Power Query Editor  
- DAX (Data Analysis Expressions)  
- Excel (for raw dataset preparation)

---

## 📂 Dataset Overview

The dataset contains transactional sales data with the following fields:

- Invoice No  
- Stock Code  
- Description (Product Name)  
- Quantity  
- Invoice Date  
- Unit Price  
- Country  
- Customer ID  

---

## 🧹 Data Cleaning & Preparation

Steps performed in Power BI:

- Filtered out records with 0 Quantity or 0 Unit Price  
- Removed transactions with missing Product Descriptions or Stock Codes  
- Handled missing Customer IDs by tagging them as "Unknown"  
- Separated Date into:
  - Date  
  - Time  
  - Month  
  - Month Name  
  - Year  
- Created new calculated columns:
  - Total Price = Quantity × Unit Price  
  - IsKnownCustomer (Boolean for presence of Customer ID)

---

## 📊 Dashboard Features

The final dashboard includes the following insights:

| Feature                   | Description                                      |
|--------------------------|--------------------------------------------------|
| 📌 KPI Cards              | Total Products Sold, Total Revenue, Unique Customers |
| 📌 Donut Chart            | Sales Distribution by Country                   |
| 📌 Line & Bar Combo Chart | Monthly Sales Quantity & Revenue Comparison     |
| 📌 Line Chart             | Monthly Revenue Trend Comparison                |
| 📌 Stacked Column Chart   | Top 5 Products Sold (Comparison by Year)        |
| 📌 Donut Chart            | Products Sold per Year                          |
| 📌 Slicers                | Filter by Product, Country, Month, and Year     |

---


## 🙌 Acknowledgements

This project was created as part of my Data Analytics Internship at Future Interns.  
Special thanks to my mentor **@Tarang Sir** for his continuous support and guidance throughout the project.

---

## 📬 Connect with Me

If you found this project helpful or interesting, feel free to connect:

📧 Email: sohomroyofficial2025@gmail.com

---

© 2025 Sohom Roy
