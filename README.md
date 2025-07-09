# Zomato-Performance-Dashboard

  ![zomato](https://github.com/user-attachments/assets/26c7fa35-3cad-420d-ad68-408e3851fe03)

This project presents an interactive Power BI dashboard for Zomato, providing a visual analysis of order trends, restaurant performance, and customer behavior. The insights support data-driven decision-making across marketing, operations, and customer experience.

---


## Description

The Zomato Analytics Dashboard is designed to help internal stakeholders understand food delivery performance, customer satisfaction, and restaurant ratings across various cities. It is a tool for improving business operations and enhancing the user experience on the Zomato platform.

---

## Business Requirement Document (BRD)

- Here is BRD File: https://github.com/imkumar77/Zomato-Performance-Dashboard/blob/main/Zomato_BRD.docx

### Project Objectives
- Provide insights into food delivery, customer satisfaction, and restaurant reviews.
- Improve decision-making for operations, marketing, and restaurant stakeholders.

### Key Performance Indicators
- **Total Orders**
- **Average Delivery Time**
- **Average Order Value (AOV)**
- **Customer Satisfaction Rating**
- **Discount Utilization Rate**

### Key Visualizations
- Order trend (line chart)
- Delivery time by city (bar chart)
- Top 10 restaurants (revenue-wise)
- Ratings distribution (bar/pie chart)
- Cuisine popularity (bar chart)

### Filters
- Date Range
- City/Location
- Cuisine Type
- Ratings
- Discount Applied

### Stakeholders
- Business Analysts
- Operations Team
- Marketing Team
- Restaurant Owners

---


## Dataset Overview

- You can get Dataset from here: https://github.com/imkumar77/Zomato-Performance-Dashboard/blob/main/Zomato.xlsx

The project uses the following datasets:

- **Orders Dataset**: Contains `Order_ID`, `Customer_Name`, `Location`, `Restaurant_Name`, `Cuisine`, `Order_Date`, `Delivery_Time`, `Order_Amount`, and `Is_Discount_Applied`.
- **Restaurant Dataset**: Includes `Restaurant_Name`, `Location`, `Ratings`, `Reviews`, and `Cuisine`.
- **Reviews Dataset**: Contains `Review_Text`, `Ratings`, `Review_Date`, and `Customer_Feedback`.


### Database Setup

- The data was loaded into Power BI from flat files (Excel/CSV).
- Power Query was used for transformation and cleaning.
- DAX was used to create calculated columns and measures.
- Relationships were established between tables based on keys such as `Restaurant_Name` and `Order_ID`.


###  Data Cleaning & Preparation

- Removed nulls and duplicates.
- Standardized categorical data like `City`, `Cuisine`, and `Rating`.
- Converted numerical fields to consistent units (e.g., INR → Millions).
- Created KPIs and calculated fields using DAX (e.g., `Average Delivery Time`, `AOV`, `Rating Bucket`).


### Exploratory Data Analysis (EDA)

Exploratory visualizations were built to examine:

- Order volume trends
- Restaurant-wise revenue
- Ratings distribution
- Cuisine performance
- Average delivery times by location


###  Analysis Objectives

- Track order and delivery performance
- Monitor restaurant reviews and customer ratings
- Understand customer behavior and preferences
- Visualize key data points for quick decision-making
- Improve operational efficiency using KPIs


### Key Concepts Used

- DAX Measures and Calculated Columns
- KPIs: Total Orders, AOV, Ratings, Delivery Time
- Conditional Formatting
- Hierarchical Filtering (Date, Location, Cuisine)
- Drill-down Analysis
- Interactive Dashboards and Slicers

### Tools & Technologies

- **Power BI Desktop**
- **Power Query**
- **DAX**
- **Microsoft Excel**
- **Data Visualization & KPI Modeling**

---

## Working Dashboard Link

  https://github.com/imkumar77/Zomato-Performance-Dashboard/blob/main/Zomato%20Performance%20Dashboard.pbix

---
  
## Insights & Findings

- Most popular cuisines: North Indian, Chinese
- Cities like Bangalore and Delhi lead in total orders
- Restaurants offering discounts perform better in order volume
- Delivery-enabled restaurants consistently receive higher ratings
- Few high-performing restaurants drive majority of revenue

---

## ✅ Conclusion

This dashboard helps Zomato's teams and stakeholders gain a consolidated view of platform performance. The findings can improve restaurant partnerships, target marketing campaigns, and fine-tune customer service strategies.

---




