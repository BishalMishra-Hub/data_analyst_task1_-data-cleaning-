# 📊 Marketing Campaign — Data Cleaning & Preprocessing  
**Task 1 | Python • Pandas • Google Colab**

Welcome to the first step of the Marketing Campaign Data Analysis project!  
This task focuses on transforming the raw dataset into a structured, clean, and analysis-ready version.

---

## 🚀 Project Overview  
The goal of this task was to clean, format, and standardize the **marketing_campaign.csv** dataset so that it’s fully prepared for further **EDA, modelling, and visualization**.

This process included handling missing values, fixing inconsistent data, converting data types, renaming columns, and generating output files.

---

## 📁 Dataset  
**File:** `marketing_campaign.csv`  
**Rows:** 2240  
**Columns:** 28+  
**Source:** Provided as part of the marketing analytics task.

---

## 🛠 Tools & Libraries  
- **Python**  
- **Pandas**  
- **Google Colab**

---

## 🔍 Steps Performed (Detailed & Interactive)

### ✅ 1. Loaded Dataset  
- Read the CSV file into a pandas DataFrame.  
- Printed dataset shape, missing values, and duplicate count.

### 🧹 2. Removed Duplicate Records  
Ensures accuracy and eliminates repeated data that may distort results.

### 🧮 3. Handled Missing Values  
- **Numeric columns** → Replaced missing values using **median**  
- **Categorical columns** → Filled missing values using **mode**  

This prevents model bias and keeps numeric distribution stable.

### 📝 4. Cleaned Text Data  
- Trimmed spaces  
- Converted all text to lowercase  

Standardizes inconsistent inputs such as `" Married"` and `"married"`.

### 📅 5. Converted Date Columns  
Converted `Dt_Customer` into proper `datetime` format for correct time-based analysis.

### 🔢 6. Converted Numeric Columns  
Applied `pd.to_numeric()` to ensure every numeric feature is machine-learning friendly.

### ✨ 7. Renamed Columns  
- Converted column names to lowercase  
- Replaced spaces with underscores  

Improves readability and prevents errors during EDA or model pipeline creation.

---

## 📦 Output Files  
| File Name | Description |
|-----------|-------------|
| `cleaned_marketing_campaign.csv` | Fully cleaned dataset |
| `changes_summary.txt` | Summary of all data-cleaning steps applied |

---

## 📘 Code Notebook  
Full Python code used in Google Colab is available inside this repository:  
> **colab_notebook_bishal1.ipynb**

The notebook includes:  
- Code cells  
- Output logs  
- Automated downloading of processed files  
- Step-by-step cleaning workflow

---

## 📈 Outcome  
The dataset is now **clean**, **consistent**, and **analysis-ready** — making it suitable for:  
- Exploratory Data Analysis  
- Machine Learning  
- Visualization  
- Dashboard building

---
