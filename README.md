# SQL-Data-Cleaning-Project
A SQL data cleaning project using MySQL to clean and prepare a real-world layoffs dataset for analysis.


# 🧹 SQL Data Cleaning Project

## 📌 Project Overview

This project demonstrates the complete data cleaning process using MySQL on a real-world layoffs dataset.

The objective was to clean raw data by removing duplicates, standardizing values, handling missing data, converting data types, and preparing the dataset for further analysis.

---

## 📂 Dataset

This project uses a real-world layoffs dataset containing information such as company, industry, location, date, total layoffs, funding raised, and layoff percentages.

The dataset was cleaned and prepared for further analysis using SQL.

---

## 🛠️ Tools Used

- MySQL
- MySQL Workbench

---

## 📚 SQL Skills Demonstrated

- Window Functions
- ROW_NUMBER()
- Common Table Expressions (CTEs)
- SELF JOIN
- UPDATE
- DELETE
- ALTER TABLE
- Data Cleaning
- Date Conversion
- String Functions

---

## 🧹 Data Cleaning Process

### 1. Removed Duplicate Records
Used `ROW_NUMBER()` to identify duplicate rows and removed them.

### 2. Standardized Data
- Removed extra spaces using `TRIM()`
- Standardized industry names
- Standardized country names

### 3. Converted Date Format
Converted the `date` column from text to the DATE data type using `STR_TO_DATE()`.

### 4. Handled Missing Values
- Converted blank values to NULL.
- Used a SELF JOIN to populate missing industry values.

### 5. Removed Unnecessary Records
Deleted rows where both `total_laid_off` and `percentage_laid_off` were NULL.

### 6. Final Cleanup
Removed the temporary `row_num` column after duplicate removal.

---

## 🎯 Skills Gained

- SQL Data Cleaning
- Window Functions
- Data Standardization
- Missing Value Handling
- Self Joins
- Data Preparation


---

## 📸 Project Screenshots

-- Removing Duplicate Records

-- Standardizing the Data

-- Handling Missing Values

-- Final Cleaned Dataset

---

## 📈 Outcome

Successfully transformed a raw layoffs dataset into a clean and analysis-ready dataset by:

- Removing duplicate records
- Standardizing text values
- Handling missing values
- Converting date formats
- Preparing the data for exploratory data analysis (EDA) and visualization

  ---

  ## 📖 What I Learned

Through this project , I strengthened my understanding of:

- Window Functions
- ROW_NUMBER()
- Common Table Expressions (CTEs)
- Self Joins
- Data Cleaning Techniques
- Handling Missing Data
- SQL Best Practices


