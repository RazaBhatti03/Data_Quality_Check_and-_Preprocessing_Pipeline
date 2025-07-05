# Data Quality Check & Preprocessing Pipeline

## Project: Exploratory Data Analysis & Data Preprocessing

This project is the **first and foundational step** in a robust machine learning pipeline. It focuses on **Exploratory Data Analysis (EDA)**, identifying **data quality issues**, and performing **essential preprocessing** that helpful models are trained on clean, consistent, and reliable data.

---

## Objective

To **detect, visualize, and resolve data quality issues** such as:

- Missing values  
- Duplicate records  
- Inconsistent data types  
- Outliers  
- Invalid entries  

This step helps **increase model accuracy**, reduce bias, and ensure reliable performance in real-world applications.

---

## Key Tasks Performed

### 1. Data Profiling & Overview
- Inspected column types and statistical summaries.
- Reviewed sample records to detect anomalies.

### 2. Missing Value Analysis
- Visualized missingness patterns.
- Quantified % of nulls in each feature.
- Made decisions on dropping/imputing based on domain logic.

### 3. Duplicate & Inconsistent Records
- Detected and removed duplicate entries.
- Standardized inconsistent category labels and text data.

### 4. Outlier Detection
- Used boxplots, histograms, and IQR methods.
- Flagged and handled extreme values appropriately.

### 5. Data Type Corrections
- Converted incorrect datatypes (e.g., object → float).
- Ensured numerical and categorical features are aligned properly.

### 6. Domain-Specific Corrections
- Identified business-logic violations.
- Cleaned incorrect or impossible values (e.g., negative ages, zero in non-zero columns).

---

##  Visual Analysis

The following visual tools were used to support data understanding:

- Heatmaps for missing data  
- Boxplots & histograms for outliers  
- Countplots for categorical distribution  
- Correlation matrices for multicollinearity checks

---

##  Business Impact

By cleaning and standardizing the data:

- We **reduced noise** and increased **signal clarity** for the machine learning models.
- We laid the foundation for **trustworthy insights** and **data-driven decisions**.
- This stage **ensures the data pipeline is production-ready**, minimizing technical debt in future stages.

---

##  Lessons Learned

- Always **visualize before you clean**.
- **Domain knowledge is critical** in determining whether to drop, impute, or transform data.
- EDA is **not just technical**, it's a **strategic tool** for identifying patterns and business anomalies.

---

##  Next Steps

This cleaned dataset will now feed into:

1. **Feature Engineering**  
2. **Model Building**  
3. **Model Tuning & Evaluation**

All future models will be built on this **preprocessed foundation** to ensure high generalization performance.

---

##  Files

- `1_EDA_checkDataQuality.ipynb` – Jupyter Notebook performing all steps above.

---

##  Conclusion

This step helped us **transform raw data into an analysis-ready format**, ensuring consistency, reliability, and interpretability — all of which are **critical to success in top-tier ML pipelines** used by MNCs.
