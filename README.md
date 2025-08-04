# 📊 Amazon Sales Data Cleaning – Internship Task 1

## 🧹 Objective
This project focuses on cleaning and preprocessing a raw Amazon sales dataset for further analysis. The original data had missing values, inconsistent formats, duplicate records, and unstandardized column names. The goal was to prepare the data for reliable analysis and visualization.

## 📁 Dataset Overview
The dataset includes information about sales transactions on Amazon, with the following columns:

- order_id  
- order_date  
- ship_date  
- status  
- customer_name  
- email_id  
- geography  
- country  
- city  
- state  
- sales  
- quantity  
- product_name  
- profit

## 🔧 Data Cleaning Steps
- ✅ Removed duplicate rows based on order_id  
- ✅ Handled missing values in email_id, sales, and profit  
- ✅ Standardized column headers to lowercase with underscores  
- ✅ Converted date formats to dd-mm-yyyy in order_date and ship_date  
- ✅ Corrected data types (dates, numbers, text)  
- ✅ Normalized text values (status, country, city, etc.)

## 🛠 Tools Used
- Microsoft Excel – for filtering, formatting, and data correction

## 📌 Outcome
A clean, well-structured Excel dataset (`cleaned_amazon_sales.xlsx`) that is ready for:
- Sales trend analysis
- Profitability metrics
- Customer segmentation
- Dashboard reporting

## 📂 Files in this Repository
- `cleaned_amazon_sales.xlsx` – Final cleaned dataset  
- `README.md` – Project summary and documentation
