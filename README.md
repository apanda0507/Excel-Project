# 📊 Excel-Based Sales and Finance Analytics Report

This project focuses on building dynamic, data-driven Excel reports to evaluate **sales performance** and **financial outcomes** across multiple business segments. By transforming raw business data into meaningful insights, it empowers organizations to make strategic decisions based on customer behavior, market dynamics, and financial trends.

---

## 🌟 Project Overview

In today's competitive business landscape, understanding **sales trends** and **financial performance** is crucial for growth and sustainability. This project was developed as a **comprehensive analysis framework** using Microsoft Excel to extract valuable insights from complex datasets.

The goal was to create powerful and intuitive reports that offer:

- Clear visibility into **customer performance**
- Insights into **market expansion opportunities**
- Key **profitability indicators**

The project turns scattered, unstructured sales and finance data into **structured, actionable intelligence** through data transformation, modeling, and visualization techniques.

---

## 🎯 Objectives

- Design **interactive Excel dashboards** for sales and financial analytics  
- Perform **data cleaning and transformation** using Excel formulas and Power Query  
- Generate **KPIs and performance metrics** for business evaluation  
- Enable **decision-making support** using dynamic visualizations and pivot tools  
- Uncover insights related to **customer trends**, **product performance**, and **financial health**

---

## ➡️ 𝐒𝐭𝐞𝐩𝐬 𝐢𝐧𝐯𝐨𝐥𝐯𝐞𝐝 𝐢𝐧 𝐦𝐚𝐤𝐢𝐧𝐠 𝐭𝐡𝐢𝐬 𝐑𝐞𝐩𝐨𝐫𝐭: -

1.𝐄𝐓𝐋 (𝐄𝐱𝐭𝐫𝐚𝐜𝐭, 𝐓𝐫𝐚𝐧𝐬𝐟𝐨𝐫𝐦 𝐚𝐧𝐝 𝐋𝐨𝐚𝐝) Load all the CSV files that were provided, to Power Query. Ensured there were no missing values, ensured each dimension table had a unique identifier column, removed duplicate values, corrected the spelling errors, and in the end loaded the files in the Power Pivot.

2.𝐃𝐚𝐭𝐚 𝐌𝐨𝐝𝐞𝐥𝐢𝐧𝐠 Connect all the tables using star schema. Create a new table called dim_date using Power Query that includes the date, month, and year in a separate column. Add a new column for adding AtliQ Hardware Fiscal year that runs from September to August and then connect the table with others.

3.𝗣𝗶𝘃𝗼𝘁 𝗧𝗮𝗯𝗹𝗲 𝗮𝗻𝗱 𝗣𝗼𝘄𝗲𝗿 𝗣𝗶𝘃𝗼𝘁 Integrate the data model with a Pivot Table for quick data analysis. Utilize Power Pivot to create new measures and columns. Employ Power Query for seamless data transformation and connectivity, streamlining the entire process of preparing and analysing data efficiently.

4.𝐃𝐀𝐗 (𝐃𝐚𝐭𝐚 𝐀𝐧𝐚𝐥𝐲𝐬𝐢𝐬 𝐄𝐱𝐩𝐫𝐞𝐬𝐬𝐢𝐨𝐧) Create 10 + new Measures such as Net sales for each year, Gross Margin, GM %, and COGS using Formulas like Calculate, Sum, Divide, etc. Create new columns using functions like RELATED, CALCULATE, and FORMAT. Also, extract quarterly months by adding 4 months to the calendar year for a fiscal year perspective.

5.𝐂𝐨𝐧𝐝𝐢𝐭𝐢𝐨𝐧𝐚𝐥 𝐅𝐨𝐫𝐦𝐚𝐭𝐭𝐢𝐧𝐠 Applied Conditional Formatting to enhance data presentation by applying rules, and Format numbers and text to highlight important data, identify trends, and improve overall readability.

---

## ✅ Key Features

- 📌 **Dynamic Dashboards** – Easily filter data by region, product, sales rep, or time period  
- 💡 **KPI Indicators** – Track revenue, profit margin, customer growth, and sales trends  
- 📈 **Trend Analysis** – Visualize monthly and quarterly performance patterns  
- 📉 **Underperformance Detection** – Identify low-performing products/customers  
- 🧠 **Actionable Insights** – Clear, strategic takeaways for business planning  

---

## 📷 Sample Screenshots

> *(Replace the image paths with actual links to your screenshots in the repo)*

![Sales Dashboard](images/sales_dashboard.png)  
*Sales Performance Dashboard with monthly trend lines and KPIs*

![Finance Overview](images/finance_overview.png)  
*Financial metrics with profitability insights and charts*

---

## 📂 Project Files

- [`Final_Sales_Report`](link-to-your-sales-file) – Interactive sales analysis dashboard  
- [`Finance_Report.xlsx`](link-to-your-finance-file) – Financial performance report with trends  
- [`Raw_Data.xlsx`](link-to-your-raw-data) – Original dataset used for transformation  

---

## 💡 𝐈𝐧𝐬𝐢𝐠𝐡𝐭𝐬:-
1. In 2021, India emerged as the top-performing market with the highest net sales of $161.3 million, while Sweden recorded the lowest sales at $1.8 million.

2. The AQ Master Wired X1 MS proved to be the best-selling product, moving 4.2 million units, whereas the AQ Home All-in-1 Gen2 had the lowest sales, with only 8.8 thousand units sold.

3. During the festive months of October to December, a notable surge in sales and profits was observed in India.

4. The top 3 customers contributing to the highest net sales were Amazon, AtliQ Exclusive, and AtliQ e-store.

5. The introduction of 16 new products in 2021 showcased AQ's innovation, with the AQ Qwerty leading sales at 22 million units.

---
