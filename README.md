<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0072ff,100:00c6ff&height=200&section=header&text=Marketing%20Campaign%20Data%20Cleaning&fontSize=45&fontColor=ffffff&animation=fadeIn" />

### 🧼 **Data Cleaning & Preprocessing — Marketing Campaign Dataset**
#### *Python • Pandas • Google Colab*

---

<img src="https://img.shields.io/badge/Domain-Data%20Cleaning-blue?style=for-the-badge" />
<img src="https://img.shields.io/badge/Dataset-Marketing%20Campaign-orange?style=for-the-badge" />
<img src="https://img.shields.io/badge/Python-3.9+-yellow?style=for-the-badge" />
<img src="https://img.shields.io/badge/Pandas-Library-success?style=for-the-badge" />
<img src="https://img.shields.io/badge/Google%20Colab-Notebook-blueviolet?style=for-the-badge" />
<img src="https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge" />

</div>

---

# 📊 Overview  

This repository contains **Task 1** of the Marketing Campaign Analytics pipeline —  
a complete **data cleaning and preprocessing workflow** performed on the `marketing_campaign.csv` dataset.

The objective was to convert raw, inconsistent, messy data into a **fully structured, readable, machine-learning-ready** dataset.

This cleaned dataset will be used in the upcoming steps of the full marketing analytics project:
- Exploratory Data Analysis (EDA)
- Machine Learning Modelling
- Customer Segmentation
- Campaign Optimization Insights

---

# 📁 Dataset Information  

| Attribute | Details |
|----------|---------|
| **File Name** | `marketing_campaign.csv` |
| **Rows** | 2240 |
| **Columns** | 28+ |
| **Source** | Provided as part of the Marketing Analytics task |

---

# 🛠 Tools & Libraries Used  

- **Python 3.9+**
- **Pandas**
- **NumPy**
- **Google Colab**

---

# 🔍 Step-by-Step Workflow  

## ✅ 1. Loaded and Inspected Dataset  
- Loaded CSV using pandas  
- Viewed column info, missing values, duplicates  
- Understood column distributions  

---

## 🧹 2. Removed Duplicate Records  
Eliminated repeated entries to ensure data accuracy.

---

## 🧮 3. Handled Missing Values  
- **Numeric Columns** → Filled using **median**  
- **Categorical Columns** → Filled using **mode**  

Ensures stable modeling and prevents null-related errors.

---

## 📝 4. Cleaned and Standardized Text Columns  
- Trimmed leading/trailing spaces  
- Converted all text to lowercase  
- Standardized categorical entries  

Example:  
`" Married"` → `"married"`

---

## 📅 5. Converted Date Columns  
Converted important date fields (e.g., `Dt_Customer`) into proper **datetime** format.

---

## 🔢 6. Converted Numeric Columns  
Used `pd.to_numeric()` to fix object-type numeric values.

---

## ✨ 7. Renamed Columns for Consistency  
- Lowercased column names  
- Replaced spaces with underscores  

Easier to use during modeling and analysis.

---

# 📦 Output Files  

| File | Description |
|------|-------------|
| **`cleaned_marketing_campaign.csv`** | Final processed dataset |
| **`changes_summary.txt`** | Logs of cleaning decisions |

---

# 📘 Notebook  

The complete step-by-step implementation is available in:

👉 **`colab_notebook_bishal1.ipynb`**

It includes:
- Cleaning code  
- Logs  
- Screenshots  
- Saved output files  

---

# 📈 Final Outcome  

After cleaning, the dataset is now:

✔ Free from duplicates  
✔ Missing values handled  
✔ Clean column names  
✔ Proper datatypes  
✔ Standardized categories  
✔ Ready for EDA, modeling, and dashboards  

This ensures a strong foundation for deeper analytics.

---

# 👨‍💻 Author  

**✦ Bishal Kumar Mishra**  
*Aspiring Data Analyst | Data Engineer | ML Enthusiast*

If this project helped you, please ⭐ star the repo!

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=transparent&fontColor=00c6ff&text=Thank%20You!&height=120&fontSize=45" />

</div>
