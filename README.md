# Data-Cleanser
# 🏥 Patient Health Records Preprocessing

![Python](https://img.shields.io/badge/Python-Data%20Analysis-blue)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)
![Focus](https://img.shields.io/badge/Focus-Missing%20Values%20%26%20Outliers-success)

## ✨ Project Overview
This project focuses on **data preprocessing** for a healthcare dataset containing **missing values** and **outliers**. The goal is to clean patient health records and prepare the dataset for **machine learning**, especially for **disease risk prediction**.

## 🎯 Objective
Apply different **missing value imputation techniques** and **outlier handling methods** to improve data quality and create a final clean dataset.

## 🩺 Problem Statement
A healthcare company has patient records with incomplete data and extreme values caused by reporting issues and measurement errors. This project cleans the dataset so it becomes suitable for further analysis and predictive modeling.

## 📊 Dataset Snapshot
- Raw dataset: **220 rows x 9 columns**
- Final cleaned dataset: **220 rows x 9 columns**
- Missing values in raw data: **111**
- Missing values after cleaning: **0**
- Target variable: **`disease_risk`**

## 🧾 Dataset Columns
- `patient_id`
- `age`
- `gender`
- `region`
- `bmi`
- `blood_pressure`
- `cholesterol`
- `glucose`
- `disease_risk`

## 🛠️ Methods Used
### Missing Value Handling
- Simple Imputer (Numerical)
- Simple Imputer (Categorical)
- Most Frequent Imputation
- Missing Indicator + Random Sample Imputation
- KNN Imputer
- MICE Algorithm

### Outlier Handling
- Z-score Method
- IQR Method
- Percentile Method
- Winsorization

## 🏆 Final Selection
- Best imputation strategy: **MICE**
- Best outlier handling method: **Winsorization**

## 📁 Project Files
- [Notebook](./patient_health_preprocessing.ipynb)
- [Raw Dataset](./data/patient_health_records.csv)
- [Cleaned Dataset](./data/patient_health_cleaned.csv)
- [Brief Report](./reports/brief_report.md)
- [Theory Report (Markdown)](./reports/theory_report.md)
- [Theory Report (PDF)](./reports/theory_report.pdf)
- [Screenshots](./screenshots/)

## 🖼️ Screenshots
### Missing Value Summary
![Missing Summary](./screenshots/02_missing_summary.png)

### Missing Value Chart
![Missing Chart](./screenshots/03_missing_values_chart.png)

### Imputation Comparison
![Imputation Comparison](./screenshots/04_imputation_comparison.png)

### Outlier Comparison
![Outlier Comparison](./screenshots/06_outlier_comparison.png)

### Final Dataset Preview
![Final Dataset](./screenshots/07_final_dataset_preview.png)

## 🚀 How to Open
1. Open `patient_health_preprocessing.ipynb` in **Jupyter Notebook**, **VS Code**, or **Google Colab**.
2. Run the cells step by step.
3. View the final cleaned dataset in `data/patient_health_cleaned.csv`.
4. Check the short report and theory files in the `reports` folder.

## ✅ Conclusion
This project shows how data preprocessing improves healthcare data quality by handling both **missing values** and **outliers**. After cleaning, the dataset becomes more reliable and more useful for machine learning tasks.
