# Task 1: Data Cleaning and Preprocessing – Netflix Titles Dataset

## 🧠 Task Objective
Clean and preprocess a raw dataset by handling missing values, removing duplicates, fixing formatting issues, and preparing it for analysis.

## 📁 Dataset Used
- Dataset Name: Netflix Movies and TV Shows
- Source: Kaggle (netflix_titles.csv)

## 🧹 Cleaning Steps Performed Using Python (Pandas)
1. **Removed Duplicate Rows** using `drop_duplicates()`.
2. **Handled Missing Values:**
   - Filled missing `director`, `cast`, and `country` values with `"Unknown"`.
3. **Converted `date_added` to datetime** using `pd.to_datetime()`.
4. **Standardized Text Fields:**
   - Lowercased and stripped `type` and `rating` fields.
   - Capitalized `country` names consistently.
5. **Renamed Columns** to `snake_case` using `str.lower()` and `str.replace()`.
6. **Extracted Duration Info:**
   - Split the `duration` column into `duration_int` and `duration_type` (e.g., 90 minutes or 2 Seasons).
7. **Fixed Data Types:**
   - Ensured `release_year` is numeric.
   - Ensured `duration_int` is numeric.

## 🔧 Tools Used
- Python 3.x
- Pandas Library

## 💾 Output
- Cleaned dataset: `cleaned_netflix_titles.csv`

## ✅ Outcome
A clean, structured, and analysis-ready dataset free from common data quality issues.

---
🧑‍💻 *Cleaned and processed by Vedant using Python and Pandas.*