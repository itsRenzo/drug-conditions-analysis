# Drugs, Side Effects, and Medical Conditions Analysis

## 📌 Project Overview

This project explores a dataset containing various drugs, their side effects, and the medical conditions they are used to treat. The aim is to clean and analyze the dataset, handle missing values, and gain insights into drug usage, alcohol interaction, ratings, and other pharmaceutical attributes through exploratory data analysis (EDA).

---

## 📁 Dataset

- **Dataset Name**: Drugs, Side Effects, and Medical Conditions
- **Dataset Source**: [Kaggle Dataset](https://www.kaggle.com/datasets/jithinanievarghese/drugs-side-effects-and-medical-condition)
- **Number of Attributes**: 17
- **Number of Rows**: 2931

---

## 🧼 Data Preprocessing

### 🔹 Attribute Selection
- Dropped irrelevant columns: `'csa'`, `'drug_link'`, `'medical_condition_url'`
- Simplified binary attributes like `'alcohol'`, `'pregnancy_category'`, and `'rx_otc'`

### 🔹 Data Cleaning
- Cleaned and standardized the `'side_effects'` column
- Filled missing values and handled outliers
- Converted skewed data to appropriate scale for analysis

---

## 📊 Exploratory Data Analysis (EDA)

### 🔍 Tasks Performed
- Checked dataset shape, data types, and null values
- Analyzed distribution of:
  - Drug ratings
  - Number of reviews
  - Alcohol interaction warnings
  - Pregnancy categories
  - Prescription vs OTC drugs
- Used visualizations:
  - Histograms
  - Boxplots
  - Count plots
  - Pie charts
  - Heatmaps

### 📈 Visualization Insights
- Ratings are skewed positively with more 10s and 9s
- Most drugs are prescription-based
- Alcohol interaction is rare but present
- Some conditions have many associated drugs, others very few

---

## 📊 Dataset Dimensions After Preprocessing

- **Rows**: 2931  
- **Columns**: 14  

---

## 🛠 Python Libraries Used

- `pandas`
- `numpy`
- `seaborn`
- `matplotlib`

---

## ✅ Notes

> 🔹 This project is focused on **EDA and data cleaning only**  

---

## 🚀 Future Enhancements

- Integrate ML models to predict side effects or drug effectiveness
- Use NLP to analyze user reviews or condition descriptions
- Build an interactive web dashboard using Streamlit

