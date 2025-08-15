# MDC-Dataverse-recruitment-task
# 📊 MDC Dataverse Recruitment Task  
## **Superstore Sales Analysis & Forecasting**  

This repository contains a **data analysis project** completed as part of a recruitment task for the **MDC Dataverse Club**.  
The project analyzes **Superstore sales data** to:  
- Understand sales performance  
- Identify trends across categories, regions, and customer segments  
- Forecast future sales using a **simple regression model**  

---

## 🎯 **Project Goal**
The primary objective is to **analyze historical sales data** to uncover insights into performance and trends, and to **build a basic forecasting model** for predicting future sales.

---

## 📂 **Dataset**
- **File:** `Sample - Superstore.csv`  
- **Details:** Contains transactional data with product details, customer information, geographical data, sales amounts, and profit values.  

---

## 🔍 **Analysis Steps**

1. **Data Loading & Inspection**  
   - Load dataset into Pandas DataFrame  
   - Check for missing values & data types  

2. **Data Cleaning & Preparation**  
   - Handle missing values  
   - Convert `Order Date` to datetime for time series analysis  

3. **Sales Performance Analysis**  
   - Calculate **total sales**, **average sale per order**  
   - Analyze **monthly** & **yearly** trends  
   - Visualize with **interactive Plotly charts**  

4. **Sales Trend Analysis by Dimensions**  
   - Product **Category**  
   - **Region**  
   - Customer **Segment**  

5. **Predictive Analysis (Simple Regression)**  
   - Aggregate sales **by month**  
   - Apply **linear regression model**  
   - Forecast next month’s sales  
   - Visualize historical sales, regression fit, and forecast  

---

## 📌 **Key Findings**

| Metric | Insight |
|--------|---------|
| **Total Sales** | $2,297,200.86 |
| **Average Sale per Order** | $458.61 |
| **Seasonality** | Sales peak towards end of the year |
| **Yearly Trend** | Steady growth from 2014 to 2017 |
| **Top Category** | Technology |
| **Top Region** | West |
| **Top Segment** | Consumer |
| **Forecast (Next Month)** | ~$68,618.19 |

---

## 🛠 **How to Run the Project**

1. **Clone this repository**  
   ```bash
   git clone https://github.com/akiharsha/MDC-Dataverse-recruitment-task.git
   cd MDC-Dataverse-recruitment-task

---

## Install Dependencies**
pip install pandas numpy plotly scikit-learn
