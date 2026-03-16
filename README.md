# E-Commerce Electronics Sales Dashboard (2019)

##  Project Overview
This project analyzes an e-commerce electronics sales dataset containing transactional records for the entire year of 2019. The dataset consists of monthly sales data across various electronic products such as phones, laptops, monitors, and accessories.

The goal of this project is to identify key sales patterns, product performance, customer purchasing behavior, and geographic trends to derive business insights.

The analysis combines **Python data preprocessing** and **Power BI visualization** to transform raw transactional data into an interactive analytics dashboard.

---

##  Dashboard Preview
<img width="1232" height="677" alt="image" src="https://github.com/user-attachments/assets/cd53882a-a6e4-4f92-ba00-7315db3a5cfe" />


---

##  Dataset
Total records: 
500,000+  
Columns: 
• Order ID 
• Product 
• Quantity Ordered 
• Price Each 
• Order Date 
• Purchase Address 

---

##  Data Cleaning & Preparation (Python)

Data preprocessing was performed using **Python (Pandas)**.

Key steps included:

- Removing empty rows and invalid records
- Converting numeric columns to proper data types
- Converting `Order Date` to datetime format
- Extracting additional analytical columns

Derived columns created:

- Sales (Quantity Ordered × Price Each)
- Month
- Hour
- City
- State
- Week Type (Weekday / Weekend)
- Product Category

### Product Categories Created

Products were grouped into broader categories for easier analysis:

- Phones
- Laptops
- Monitors
- Charging Accessories
- Batteries
- TV
- Other

---

##  Exploratory Data Analysis

The following analytical questions were explored:

1. What is the total revenue generated in 2019?
2. Which product categories generate the highest revenue?
3. Which cities produce the highest sales?
4. What time of day do customers place the most orders?
5. How do sales differ between weekdays and weekends?
6. What are the monthly sales trends across the year?

---

##  Power BI Dashboard

An **interactive E-Commerce Sales Dashboard** was created using Power BI.

### Key Performance Indicators

- Total Revenue
- Total Orders
- Total Quantity Sold
- Average Order Value

### Visual Insights

- Revenue by Product Category
- Sales by City
- Monthly Sales Trend
- Orders by Hour of Day
- Weekday vs Weekend Sales Comparison

### Interactive Filters

Users can dynamically filter the dashboard using:

- Product Category
- City

---

##  Key Insights

- Total revenue for 2019 exceeded **$103 million**.
- **Phones and laptops** generate the largest share of revenue.
- **San Francisco and Los Angeles** are the top-performing cities in terms of sales.
- Customer purchases peak during **11 AM–1 PM and 6 PM–8 PM**, indicating the best times for advertising.
- Sales activity is **higher during weekdays compared to weekends**.
- **December recorded the highest sales**, likely due to holiday shopping trends.

---

##  Tools & Technologies

- Python
- Pandas
- Power BI

