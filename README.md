# NYC Motor Vehicle Crash Severity Analysis 🚦

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)  
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)  
![License](https://img.shields.io/badge/License-Educational-lightgrey)  

[![Download Report](https://img.shields.io/badge/Download-Report-red)](Report.pdf)  
[![Download Slides](https://img.shields.io/badge/Download-Slides-blue)](Presentation_slides.pdf)  

**Course:** EMSE 6574 – Programming for Analytics  
**Instructor:** Michael Rossetti  
**Team Members:**  
- Vidyullatha Kavilukodige Sathishrao (GWID: G44335744)  
- Taekwon Choi (GWID: G27747799)  
**Date:** December 12, 2025  

---

## 📌 Project Overview

This project analyzes **100,000 NYC motor vehicle crash records** (Oct 2024 – Dec 2025) to **predict high-severity crashes**, defined as:

- ≥1 fatality **or**  
- ≥2 injuries  

The dataset includes crash location, time, victim types, contributing factors, and engineered features such as **hour, day of week, weekend/rush hour, and victim flags**.

---

## 🗂 Repository Contents

| File | Description |
|------|-------------|
| `Report.pdf` | Detailed project report with analysis, results, and reflections |
| `ML_Model.ipynb` | Jupyter Notebook: data cleaning, EDA, feature engineering, ML models |
| `Presentation_slides.pdf` | Project presentation with key findings and visualizations |

---

## ⚡ Key Features & Methods

- Explored **geographic, temporal, and victim-based patterns** in crashes  
- Engineered features: hour, day of week, weekend, rush hour, victim flags  
- Machine Learning Models:
  - Logistic Regression (with/without SMOTE)  
  - Random Forest (with/without SMOTE)  
  - Gradient Boosting  
- Evaluation metrics: **ROC AUC, Precision, Recall, F1 Score**  
- Focused on **maximizing recall** for severe crashes  

---

## 🔍 Key Findings

- **Logistic Regression** offered the best balance of recall and ROC AUC  
- Most severe crashes occurred **late at night**, not during rush hours  
- Critical contributing factors: **Lost Consciousness, Illness, Unsafe Speed**  
- Feature engineering and data cleaning significantly improved model performance  

---

## 🚀 Future Work

- Add **weather, road type, and traffic volume** features  
- Explore **class-weighted models, XGBoost, and advanced resampling**  
- Tune prediction thresholds for better recall of severe crashes  

---

## 💻 How to Run

1. Clone the repo:  
```bash
git clone https://github.com/vidyullathaks/NYC-Crash-Severity-Analysis.git
```

---

## 📄 License

Educational use only - completed as part of George Washington University coursework.

