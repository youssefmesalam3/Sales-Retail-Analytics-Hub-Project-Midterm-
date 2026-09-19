# 📊 Sales & Retail Analytics Hub

An interactive **Sales & Retail Analytics Dashboard** developed using **Microsoft Power BI** to analyze sales performance, profitability, products, customers, regions, stock items, and employee performance across the period from **2013 to 2016**.

The project started with complete **data cleaning and transformation using Excel Power Query**, followed by importing the cleaned data into Power BI, building a **Star Schema data model**, creating multiple **DAX measures**, and developing an interactive multi-page Power BI dashboard.

---

## 📌 Project Overview

The **Sales & Retail Analytics Hub** provides a comprehensive view of business performance across different dimensions, including:

- Sales
- Profit
- Orders
- Customers
- Products
- Stock Items
- Regions
- Cities
- State Provinces
- Employees
- Credit Categories
- Sales Categories
- Buying Packages

The dashboard enables users to explore business performance interactively and analyze different aspects of sales and retail operations.

---

## 🎯 Project Objectives

The main objectives of this project are to:

- Analyze overall sales performance.
- Monitor total profit and profitability.
- Track orders and quantity sold.
- Analyze product and stock item performance.
- Identify top-performing stock items.
- Analyze customer purchasing behavior.
- Evaluate customer credit categories.
- Analyze sales performance across regions and cities.
- Compare sales performance by state province.
- Analyze employee sales performance.
- Identify top-performing employees.
- Analyze sales by buying package.
- Provide interactive business insights through Power BI.

---

## 🧹 Data Cleaning & Transformation

The complete data cleaning process was performed using **Microsoft Excel and Power Query** before importing the data into Power BI.

### Power Query was used for:

- Data Cleaning
- Data Transformation
- Handling data inconsistencies
- Preparing dimension tables
- Preparing the fact table
- Formatting and standardizing fields
- Creating the final cleaned datasets
- Preparing the data for Power BI modeling

After completing the cleaning and transformation process, the cleaned datasets were exported and imported into **Power BI** for further analysis.

---

## 🏗️ Data Modeling

After importing the cleaned data into Power BI, a structured **Star Schema** was created.

The data model was designed around the sales fact table and connected dimension tables.

### Main Tables

- **FactSale**
- **DimDate**
- **DimCity**
- **DimCustomer**
- **DimEmployee**
- **DimStockItem**

The Star Schema structure was used to create a clean and efficient analytical model and to ensure that filters and calculations work correctly across the dashboard.

---

## 🧮 DAX

Multiple **DAX measures** were created in Power BI to calculate the main business metrics and support dynamic analysis.

The measures were used for:

Total Sales
Total Sales Including Tax
Total Profit
Total Cost
Total Tax
Total Quantity
Total Orders
Total Customers
Total Products Sold
Total Salespersons
Average Order Value
Average Unit Price
Profit Margin %
Average Profit per Order
Avg Quantity per Order
Total Dry Items
Total Chiller Items
Dry Items %
Chiller Items %
Sales LY
YoY Sales
YoY Sales %
Profit LY
YoY Profit
YoY Profit %

These measures were used throughout the different dashboard pages to provide dynamic and interactive calculations.

---

# 📑 Dashboard Pages

---

## 🏠 1. Overview

The **Overview** page provides a high-level summary of the company's sales and retail performance between **2013 and 2016**.

### Key Performance Indicators

- **Total Sales:** 19.88M
- **Total Profit:** 9.92M
- **Total Orders:** 8.19K
- **Total Customers:** 402
- **Total Quantity:** 1.03M
- **Total Cost:** 9.96M

### Visualizations

- Total Sales and Total Profit by Month
- Total Sales by Year
- Total Sales by Sales Category
- Stock Items Performance
- Total Sales by Stock Item
- Total Profit
- Total Quantity
- Average Unit Price
- Average Profit per Order
- Total Products
- Total Quantity by Color
- Count of Stock Items by Buying Package
- Top 10 Stock Items by Sales
- Top 10 Stock Items by Orders

### Interactive Filters

- Year
- State Province
- Sales Category
- Stock Item
- Color

<img width="1311" height="652" alt="Overview" src="https://github.com/user-attachments/assets/b04f21f8-e2c0-4685-a5b1-dc142a887475" />

---

## 📦 2. Products Analysis

The **Products** section focuses on analyzing product and stock item performance.

### Key Metrics

- Total Sales
- Total Profit
- Total Quantity
- Total Products
- Average Unit Price
- Average Profit per Order

### Visualizations

- Count of Stock Items by Buying Package
- Total Sales by Buying Package
- Total Sales, Total Profit and Total Quantity by Stock Item
- Total Quantity by Color
- Top 10 Stock Items by Sales
- Top 10 Stock Items by Orders

### Product Analysis

This section allows users to identify:

- Top-performing stock items by sales.
- Top stock items by number of orders.
- Stock item profitability.
- Quantity sold by color.
- Sales distribution by buying package.
- Product performance across different years.


<img width="1304" height="652" alt="Products" src="https://github.com/user-attachments/assets/34b83957-089a-4763-820f-3ec825954865" />
  

---

## 👥 3. Customers Analysis

The **Customers** section focuses on customer behavior and sales contribution.

### Key Performance Indicators

- **Total Sales:** 19.88M
- **Total Profit:** 9.92M
- **Average Order Value:** 2.43K
- **Average Revenue per Customer:** 49.45K
- **Total Quantity:** 1.03M
- **Total Customers:** 402

### Visualizations

- Total Sales by Buying Package
- Total Sales by Credit Category
- Total Customers by Credit Category
- Total Sales by Customer
- Top Customers by Sales

### Credit Analysis

The dashboard categorizes customers into:

- High Credit
- Low Credit

It also compares:

- Customer count by credit category
- Total sales by credit category

<img width="1309" height="661" alt="Customers" src="https://github.com/user-attachments/assets/02df0433-0f13-413f-ad4b-01cdeb417d0a" />

---

## 🌍 4. Regions Analysis

The **Regions** section focuses on geographical and employee sales performance.

### Key Performance Indicators

- Total Sales
- Total Profit
- Average Unit Price
- Average Quantity per Order
- Total Quantity
- Total Cities

### Visualizations

- Top 10 Cities by Sales
- Total Sales by State Province
- Total Sales by Employee
- Total Sales & Profit by Employee
- Total Profit by State Province
- Total Sales by Cities

### Geographic Analysis

The dashboard analyzes sales across:

- California
- Washington
- Alaska
- Oregon
- Nevada
- Hawaii

It also provides city-level analysis to identify locations with higher sales activity.


<img width="1306" height="659" alt="Regions" src="https://github.com/user-attachments/assets/c2145aac-beaf-4b6f-a3d1-a158915255b2" />

---

# 📈 Key Business Metrics

The dashboard tracks several important business KPIs:

### Sales

- Total Sales
- Sales by Year
- Sales by Month
- Sales by Region
- Sales by State
- Sales by City
- Sales by Customer
- Sales by Product
- Sales by Employee

### Profitability

- Total Profit
- Profit Margin
- Profit by State
- Profit by Employee
- Profit by Stock Item
- Profit per Order

### Customer Metrics

- Total Customers
- Average Revenue per Customer
- Average Order Value
- Customers by Credit Category
- Sales by Customer

### Product Metrics

- Total Products
- Total Quantity
- Average Unit Price
- Quantity by Color
- Sales by Stock Item
- Orders by Stock Item
- Buying Package Analysis

### Regional Metrics

- Total Cities
- Sales by State Province
- Profit by State Province
- Top Cities by Sales
- Sales by Employee

---

# 🎨 Dashboard Features

The Power BI dashboard includes:

- Interactive KPI Cards
- Interactive Slicers
- Dynamic Filters
- Bar Charts
- Column Charts
- Line Charts
- Donut Charts
- Tables
- Maps
- Top N Analysis
- Comparative Analysis
- Drill-down Analysis
- Cross-Visual Interactions

### Interactive Filters

Users can dynamically filter the dashboard using dimensions such as:

- Year
- State Province
- Sales Category
- Stock Item
- Color
- Credit Category
- Buying Package

---

# 📊 Overall Business Analysis

The dashboard covers business performance across the period from **2013 to 2016**.

The overall dataset contains:

- **19.88M Total Sales**
- **9.92M Total Profit**
- **8.19K Total Orders**
- **402 Total Customers**
- **1.03M Total Quantity**
- **9.96M Total Cost**
- **671 Total Products**
- **3,396 Total Cities**

These metrics provide a consolidated view of the company's sales and retail operations.

---

# 💡 Business Questions Answered

The dashboard helps answer questions such as:

- What is the total sales and profit performance?
- How do sales change across different years?
- Which months generate higher sales?
- Which sales category contributes most to total sales?
- Which stock items generate the highest sales?
- Which stock items receive the highest number of orders?
- How are sales distributed across buying packages?
- How does quantity vary by product color?
- How many customers belong to each credit category?
- Which customers generate the highest sales?
- Which cities generate the highest sales?
- Which state provinces contribute most to sales?
- Which employees generate the highest sales?
- How does employee sales performance compare with profit?
- How is the company's sales performance distributed geographically?

---

# 🔄 End-to-End Project Workflow

The complete project followed this workflow:

```text
Raw Data
   ↓
Excel
   ↓
Power Query
   ↓
Data Cleaning & Transformation
   ↓
Cleaned Data
   ↓
Power BI
   ↓
Star Schema Data Modeling
   ↓
DAX Measures
   ↓
Data Analysis
   ↓
Interactive Visualizations
   ↓
Power BI Dashboard

-----------------------------------------------------------------

| Technology          | Purpose                                 |
| ------------------- | --------------------------------------- |
| **Microsoft Excel** | Initial data preparation                |
| **Power Query**     | Data cleaning and transformation        |
| **Power BI**        | Data analysis and dashboard development |
| **DAX**             | Measures and analytical calculations    |
| **Data Modeling**   | Building the analytical model           |
| **Star Schema**     | Structuring fact and dimension tables   |

----------------------------------------------------------------

📁 Project Structure
Sales-Retail-Analytics-Hub/
│
├── Sales Performance Analytics Project.pbix
├── Cleaned Data/
│   ├── DimCity.xlsx
│   ├── DimCustomer.xlsx
│   ├── DimDate.xlsx
│   ├── DimEmployee.xlsx
│   ├── DimStockItem.xlsx
│   └── FactSale.xlsx
│
├── Dashboard Screenshots/
│   ├── Overview.png
│   ├── Products.png
│   ├── Customers.png
│   └── Regions.png
│
└── README.md

===================================================================

🏁 Conclusion

The Sales & Retail Analytics Hub demonstrates a complete end-to-end Business Intelligence workflow, starting from data cleaning and transformation in Excel Power Query, followed by importing the cleaned data into Power BI, building a structured Star Schema data model, creating multiple DAX measures, and finally developing an interactive multi-page dashboard.

The final solution provides a comprehensive analysis of sales, profit, products, customers, stock items, regions, cities, and employee performance, allowing users to explore the data interactively and gain meaningful business insights.

👨‍💻 Author

Youssef Mesalam

Data Analyst | Business Intelligence (BI) Developer

Skills: Power BI | DAX | Power Query | Data Modeling | SQL | Excel | Python | Data Analysis | Business Intelligence
