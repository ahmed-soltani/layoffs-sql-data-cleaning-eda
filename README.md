# SQL Layoffs Dataset – Data Cleaning & Exploratory Analysis

This project showcases a complete data cleaning and exploratory data analysis (EDA) pipeline using SQL on a real-world dataset of layoffs.

## 📁 Project Structure

- `data/` – Contains the raw dataset used in this project (`layoffs.csv`).
- `cleaning/` – Step-by-step SQL scripts for cleaning the data:
  - Handling null and blank values
  - Removing duplicates
  - Dropping unnecessary columns and rows
  - Standardizing data formats
- `eda/` – Contains the EDA SQL script exploring trends and insights from the cleaned dataset.

## 🛠️ Tools Used

- MySQL
- SQL (standard ANSI)
- Excel (for initial preview)

## 🧹 Data Cleaning Highlights

- Removed exact and near duplicates
- Replaced or handled NULLs and blank strings
- Standardized date and text fields for consistency
- Removed irrelevant or redundant columns and rows

## 📊 EDA Highlights

- Identified layoffs distribution across time, location, and industries
- Explored correlations between company size, funding stage, and layoff patterns
- Used `GROUP BY`, `CASE WHEN`, and `JOINs` to derive insights

## 📌 Motivation

This project was created to demonstrate practical SQL skills in real-world data preparation and analysis workflows, useful in data analyst and BI roles.

---

