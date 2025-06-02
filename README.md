# Task-1-Customer-Personality-Analysis
In this task, I cleaned a raw dataset using Python (Pandas). I handled missing values, removed duplicates, standardized text formats, corrected date formats, renamed columns, and fixed data types. This helped transform messy data into a clean and structured form, ready for analysis or modeling. 
🧹 Data Cleaning & Preprocessing – Customer Personality Dataset

📌 Objective
Clean a raw dataset by handling:
- Missing values
- Duplicate records
- Inconsistent text/date formats
- Column naming and data types
---
Tools Used
- Python (Pandas)
- Jupyter Notebook
- CSV dataset (Customer.csv)
---
🔧 Cleaning & Preprocessing Steps

1. Missing Value Treatment
- Filled `Income` with its mean.
- Filled `Gender` with its mode.

 2. Duplicate Records
- Removed using `drop_duplicates()`.

3. Text Standardization
- Fixed inconsistent gender entries (e.g., `male`, ` Male`, `FEMALE` → `Male`, `Female`).

4. Date Conversion
- Standardized date format (e.g., `Dt_Customer` to `datetime64`).

5. Column Renaming
- Converted to lowercase, removed spaces (e.g., `Customer ID` → `customer_id`).

6. Data Types
- Converted `Age` to integer.
- Converted date column to datetime format.
---
📁 data-cleaning-and-preprocessing/
│
├── Customer.csv                        # Raw dataset
├── cleaned_customer_data.csv           # Cleaned dataset after preprocessing
├── data_cleaning_preprocessing.ipynb   # Jupyter Notebook with all code
├── screenshots/
│   ├── 01_missing_values_check.png
│   ├── 02_before_cleaning.png
│   ├── 03_after_cleaning.png
│
├── README.md                           # Summary and explanation


 Screenshots
Included in the `screenshots/` folder:
- Before Cleaning
- Missing Value Check
- After Cleaning
---
📂 Files in This Repo
- `marketing_campaign.csv` – Raw dataset
- `marketing_campaign_cleaned.csv` – Final cleaned dataset
- `data_cleaning_preprocessing.ipynb` – Jupyter Notebook
- `README.md` – Task documentation
- `screenshots/` – Visual proof of cleaning
---
🎓 What I Learned

✅ How to:
- Identify & fix missing values with `fillna()`
- Remove duplicates
- Standardize inconsistent text entries
- Convert and standardize date/time formats
- Rename columns to clean formats
- Check & convert data types

✅ Why:
- Clean data is essential before performing analysis or modeling
- Helps avoid biased insights and errors

---
 Conclusion
This project helped me build confidence in real-world data preparation using Python. I now understand how important clean, consistent data is in any data science or machine learning workflow.
