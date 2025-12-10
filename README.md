# 📊 Customer Shopping Behavior – Data Analytics Project
## 📝 Overview

This project provides an end-to-end data analytics workflow, starting from loading and cleaning raw data in Python, performing Exploratory Data Analysis (EDA), handling missing values, renaming columns, integrating the cleaned data into a MySQL database, running SQL queries to derive insights, and finally visualizing results through a Power BI dashboard.
The goal is to extract meaningful business insights from customer shopping behavior.

## 📂 Dataset

- Total Rows: (e.g., 3,900)

- Total Columns: (e.g., 18)

- Key Features:

  Customer demographics (age, gender, location)

  Shopping behavior (preferred category, item purchased, amount spent)

  Review rating, shipping type, frequency of purchases

  Discount usage, subscription status

- Missing Values:

Missing values handled in numeric and categorical fields (e.g., Review Rating)

## 🛠 Tools & Technologies

- Data Loading & EDA  ->  Python, Pandas
- Data Cleaning  ->  Pandas
- Database Integration  ->  MySQL Server, mysql-connector / SQLAlchemy
- SQL Analysis  ->  MySQL Workbench
- Dashboard  -> 	Power BI
- Presentation  -> 	Gamma
  
## 🔍 Steps Performed
#### 1️⃣ Data Loading (Python)

- Imported dataset using pandas

- Performed initial inspection using df.head(), df.info(), and df.describe()

#### 2️⃣ Exploratory Data Analysis (EDA)

- Distribution analysis (age, amount spent, ratings)

- Category-wise product performance

- Correlation heatmaps

- Detecting and understanding outliers

#### 3️⃣ Data Cleaning

- Handled missing values

- Numerical: filled using median

- Categorical: filled using mode

- Standardized and renamed column names for uniformity

- Removed redundant or irrelevant columns

- Created derived features (example: age groups, purchase frequency)

#### 4️⃣ Integrating Data with MySQL

- Connected Python to MySQL using mysql.connector or SQLAlchemy

- Created database and tables

- Loaded cleaned dataframe into MySQL

- Validated insertion using SELECT queries

#### 5️⃣ SQL Queries for Business Insights

- Examples include:

- Revenue by gender, location, and product category

- Top 5 most purchased products

- Shipping type vs purchase amount analysis

- Subscriber vs non-subscriber spending patterns

- Repeat customer analysis

- Season-wise sales comparison

#### 6️⃣ Power BI Dashboard

- Created a fully interactive dashboard featuring:

- Total revenue overview

- Customer segmentation

- Category-wise and gender-wise insights

- Most-selling products

- Seasonality and trend analysis

#### 7️⃣ Final Presentation (Gamma)

- A professional slide deck summarizing:

- Problem definition

- Methodology

- Key insights

- Dashboard highlights

- Recommendations

## 📈 Dashboard Preview

The Power BI dashboard showcases the entire data story interactively:

- KPI cards

- Bar Charts

- Slicers & filters

- Insight-driven visuals
  
<img width="1295" height="722" alt="Screenshot 2025-12-09 225057" src="https://github.com/user-attachments/assets/a34082bd-7cd4-46db-b7fe-3486e5bba47d" />


## 🧠 Results & Insights

- Identified top customer segments contributing maximum revenue

- Found products and categories with highest demand

- Determined effect of subscription and discounts

- Discovered spending patterns across seasons, age groups, and genders

- Derived actionable recommendations for business growth
