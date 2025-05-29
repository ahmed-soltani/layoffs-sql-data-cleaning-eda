# SQL Layoffs Dataset – Data Cleaning & Exploratory Analysis

This project demonstrates a full SQL-based data cleaning and EDA pipeline using a real-world layoffs dataset. It showcases practical SQL techniques to prepare data for analysis and uncover insights into mass layoffs across industries, countries, and funding stages.

## 📁 Project Structure

- `data/` – Contains the raw dataset (`layoffs.csv`)
- `cleaning/` – Step-by-step cleaning scripts:
  - `remove_duplicates.sql`
  - `standardize_data.sql`
  - `null_blank_values.sql`
  - `remove_unnecessary_cols_rows.sql`
- `eda/` – Contains `EDA.sql` with queries for time trends, industry impact, rolling totals, and rankings.

## 🔧 Tools Used

- MySQL
- SQL CTEs, `ROW_NUMBER()`, `STR_TO_DATE()`, `GROUP BY`, `DENSE_RANK()`

## 🧹 Cleaning Highlights

- Removed duplicate entries using window functions
- Standardized inconsistent text values and converted date formats
- Filled or removed null and blank values responsibly
- Prepared clean dataset for analysis

## 📊 EDA Highlights

- Identified the most affected companies, industries, and countries
- Analyzed temporal patterns of layoffs (yearly, monthly, rolling totals)
- Explored correlations with funding stages and time
- Ranked companies per year by layoff count using `DENSE_RANK()`

## 🎯 Goal

To showcase strong foundational SQL skills in both **data preparation** and **analysis**, applicable to data analyst and BI-focused roles.
