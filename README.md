# Walmart Sales Data Analysis: Comprehensive SQL and Python Workflow

## Project Summary

![Project Pipeline](https://github.com/najirh/Walmart_SQL_Python/blob/main/walmart_project-piplelines.png)

This project delivers a full-scale data analysis workflow using Walmart’s sales data. It combines Python for data ingestion, cleaning, and feature engineering with advanced SQL querying for business insight generation. It’s tailored for data analysts aiming to sharpen skills in data wrangling, SQL, and building end-to-end data pipelines.

---

## Workflow Overview

### 1. Environment Setup  
- **Tools:** Visual Studio Code, Python, MySQL, PostgreSQL  
- **Objective:** Establish a clean, modular project workspace facilitating coding and data management.

### 2. Configure Kaggle API  
- Retrieve your Kaggle API key from your account settings.  
- Place the `kaggle.json` file in the appropriate directory.  
- Use Kaggle CLI commands to download Walmart sales datasets directly into your project folder.

### 3. Data Acquisition  
- Download Walmart sales data from Kaggle:  
  [Walmart Sales Dataset on Kaggle](https://www.kaggle.com/najir0123/walmart-10k-sales-datasets)  
- Organize datasets inside the `data/` directory for easy access.

### 4. Install Dependencies & Load Data  
- Install required Python packages:  
  `pandas`, `numpy`, `sqlalchemy`, `mysql-connector-python`, `psycopg2`  
- Load datasets into Pandas DataFrames for initial exploration.

### 5. Initial Data Exploration  
- Perform exploratory analysis using `.info()`, `.describe()`, `.head()` to understand data shapes, types, and summary statistics.

### 6. Data Cleaning & Preprocessing  
- Remove duplicate records to ensure data quality.  
- Handle missing values appropriately via removal or imputation.  
- Standardize data types, such as converting dates and currency fields.  
- Validate consistency and prepare data for analysis.

### 7. Feature Creation  
- Compute new features like `Total Amount` by multiplying unit price by quantity.  
- Enhance dataset richness to support SQL aggregations.

### 8. Data Loading to Databases  
- Establish connections to MySQL and PostgreSQL via SQLAlchemy.  
- Create tables and insert cleaned data programmatically.  
- Confirm successful data load via test queries.

### 9. SQL-Based Business Analysis  
- Craft complex SQL queries addressing core business questions:  
  - Tracking revenue trends by region and product category  
  - Identifying top-selling products  
  - Analyzing sales patterns by city, time period, and payment type  
  - Profit margin insights per store and category  
- Document each query’s purpose and findings clearly.

### 10. Documentation & Publishing  
- Maintain detailed project notes and code documentation using Markdown and/or Jupyter notebooks.  
- Share the project via GitHub with essential files: scripts, notebooks, and README.

---

## System Requirements

- Python 3.8 or above  
- MySQL and PostgreSQL database servers  
- Python libraries: `pandas`, `numpy`, `sqlalchemy`, `mysql-connector-python`, `psycopg2`  
- Kaggle API credentials for dataset access

---

## Quick Start

```bash
git clone <repository-url>
pip install -r requirements.txt
