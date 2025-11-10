# 📁 **E-Commerce Data Analysis & Feature Engineering**

## 👨‍💻 Author: **Rutwik Ramdham**

A complete end-to-end data preprocessing workflow performed on an **E-commerce dataset** to make it ready for machine-learning tasks.
This project covers **data cleaning, EDA, handling skewness, outlier removal, encoding, and feature engineering.**

---

## 📌 **Project Overview**

The goal of this project was to analyze and clean an e-commerce dataset and engineer meaningful features to support ML-based analysis, insights, and modeling.

---

## ✅ **Key Objectives**

✔ Data cleaning & preprocessing
✔ Exploratory Data Analysis (EDA)
✔ Outlier handling
✔ Skewness reduction
✔ Feature engineering
✔ Preparing ML-ready dataset
✔ Save clean data to Excel

---

## 🧹 **Data Cleaning**

| Step | Action                                       |
| ---- | -------------------------------------------- |
| 1    | Removed duplicate rows                       |
| 2    | Filled missing values (median strategy)      |
| 3    | Standardized string formats & trimmed spaces |
| 4    | Corrected wrong/mixed data types             |
| 5    | Clean indexing & dropped unwanted columns    |

---

## 🔍 **Exploratory Data Analysis (EDA)**

Key analyses performed:

* Statistical summary
* Checking distribution of numerical features
* Skewness before & after transformation
* Category frequency analysis
* Relationship of price, quantity, & sales
* Visual analytics

---

## 📉 **Outlier Treatment**

Method used:
✅ **IQR (Interquartile Range)**
→ Applied Winsorization to cap extreme values

---

## ➗ **Skewness Reduction**

Performed **Log transformation** on selected skewed variables
✅ Validated improvement using **skew() before & after**

Example:

```python
skewness_beforelogprice = skew(df['ProductPrice'])
print("Skewness before:", skewness_beforelogprice)
```

---

## 🧠 **Feature Engineering**

| Feature | Description               |
| ------- | ------------------------- |
| `Sales` | `ProductPrice × Quantity` |

Also performed:

* One-Hot Encoding for categorical variables
* Created ML-friendly dataset

---

## 📂 Folder / File Structure

```
📁 Ecommerce-EDA-FeatureEngineering
│
├── ecommerce_EDA.ipynb
├── ecommerce_dataset.xlsx
├── Rutwik_Ramdham_Ecommerce_dataset_cleaned.xlsx
└── README.md
```

---

## 🛠️ **Tech Stack**

| Tool         | Purpose            |
| ------------ | ------------------ |
| Python       | Primary language   |
| Pandas       | Data Cleaning      |
| NumPy        | Numerical Ops      |
| SciPy        | Skewness           |
| Scikit-Learn | Encoding / Scaling |
| Matplotlib   | Visualization      |
| Seaborn      | Visualization      |
| Excel        | File Export        |

---

## 📊 Output/Deliverables

✔ Cleaned Dataset
✔ Missing values handled
✔ Outliers treated
✔ Log-normalized variables
✔ Encoded categorical fields
✔ Engineered features
✔ Organized Excel export

---

## 📁 Final Cleaned File

✅ `Rutwik_Ramdham_Ecommerce_dataset_cleaned.xlsx`
→ Ideal for modeling & dashboarding

---

## 🚀 Next Steps (Future Scope)

* Build ML models: prediction / customer segmentation
* Dashboard using Power BI / Tableau
* Business insights summary

---

## ⭐ Key Learnings

✅ Real-world data is messy — preprocessing matters
✅ Skewness reduction helps model performance
✅ Feature engineering adds business value
✅ Encoding prepares data for ML

---

## 🏁 Conclusion

This project demonstrates a **complete real-world data preprocessing workflow**, making the dataset structured, enriched, and ready for analytics + ML.

---
