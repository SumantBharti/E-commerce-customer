# E-commerce-customer
Customer project in E-commerce
# 🛍️ E-commerce Customer Analysis

A complete Python-based data cleaning and feature engineering project for analyzing customer data from an E-commerce platform. The project involves handling missing values, fixing data types, treating outliers, and generating insightful features for analytics or machine learning.

---

## ✅ Project Overview

This project performs the following key tasks:

### 📌 1. Data Quality Assessment
- Preview dataset shape, memory usage, and data types
- Check for missing values and duplicate rows
- View basic statistics for numeric and categorical columns
- Visualize missing data using a heatmap

### 📌 2. Data Cleaning
- Fill missing values in numeric columns using median or mean
- Fill missing categorical fields using mode
- Drop rows with missing `CustomerID`
- Remove exact duplicate records

### 📌 3. Fixing Data Types
- Convert date fields like `registration_date`, `last_order_date` to `datetime`
- Normalize boolean fields like `is_premium`
- Standardize `Gender` to lowercase

### 📌 4. Text Preprocessing
- Clean names (capitalize and strip whitespace)
- Standardize emails and phone numbers
- Remove special formatting from phone numbers

### 📌 5. Outlier Detection & Treatment
- Detect outliers in columns like `AnnualIncome` using IQR
- Visualize outliers using boxplots
- Remove extreme values for cleaner distribution

### 📌 6. Feature Engineering
- Create `age_group`: Teen, Young Adult, Adult, Mid Age, Senior
- Create `income_bracket`: Low, Medium, High, Very High

---

## 🚀 Getting Started

### ✅ Prerequisites

Install these Python libraries before running the script:

```bash
pip install pandas numpy matplotlib seaborn
