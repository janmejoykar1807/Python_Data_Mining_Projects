# ⛏️ Python Data Mining Projects

> **Four end-to-end data mining projects** covering classification, regression, and clustering — built with Python and Scikit-Learn on real-world datasets.

---

## 📌 Overview

This repository contains a collection of data mining projects completed using Python and Jupyter Notebooks. Each project tackles a distinct analytical problem — from spam detection to salary prediction — and demonstrates a full workflow: data exploration, preprocessing, model building, and evaluation.

| # | Project | Technique | Dataset |
|---|---------|-----------|---------|
| 1 | Utility Company Segmentation | K-Means Clustering | Utilities |
| 2 | Airfare Price Prediction | Multiple Linear Regression | Airfares |
| 3 | Baseball Salary Prediction | Regression + Feature Selection | Baseball Hitters |
| 4 | Spam Email Detection | Naive Bayes / Logistic Regression | SpamBase |

---

## 📂 Repository Structure

```
Python_Data_Mining_Projects/
│
├── Data_mining_pj1(Utilities).ipynb       # K-Means clustering on utility companies
├── Data_mining_pj2(Airfares).ipynb        # Regression analysis on airfare pricing
├── Data_mining_pj3(Baseball_Hitters).ipynb # Salary prediction for baseball players
├── Data_mining_pj4(SpamBase).ipynb        # Spam email classification
│
├── Utilities.csv
├── Airfares.csv
├── Hitters.csv
└── Spambase.csv
```

---

## 🔍 Project Details

---

### 📊 Project 1 — Utility Company Segmentation
**File:** `Data_mining_pj1(Utilities).ipynb`
**Technique:** K-Means Clustering

Groups utility companies into behavioral clusters based on operational and financial metrics. Explores the optimal number of clusters using the elbow method and silhouette scores.

**Highlights:**
- Feature scaling and normalization
- K-Means with elbow method for optimal k
- Cluster profiling and business interpretation

---

### ✈️ Project 2 — Airfare Price Prediction
**File:** `Data_mining_pj2(Airfares).ipynb`
**Technique:** Multiple Linear Regression

Predicts airfare prices based on route characteristics (distance, competition, market type). Explores which factors most strongly influence ticket pricing.

**Highlights:**
- Exploratory Data Analysis (EDA) with correlation heatmaps
- Multiple linear regression with feature significance testing
- Residual analysis and model diagnostics

---

### ⚾ Project 3 — Baseball Salary Prediction
**File:** `Data_mining_pj3(Baseball_Hitters).ipynb`
**Technique:** Regression + Feature Selection

Predicts baseball player salaries using performance statistics. Applies feature selection techniques to identify the most predictive stats.

**Highlights:**
- Handling missing values and log transformation of salary
- Stepwise/regularized feature selection
- Model comparison and performance evaluation (R², RMSE)

---

### 📧 Project 4 — Spam Email Detection
**File:** `Data_mining_pj4(SpamBase).ipynb`
**Technique:** Classification (Naive Bayes / Logistic Regression)

Classifies emails as spam or not spam using 57 word/character frequency features from the UCI SpamBase dataset.

**Highlights:**
- Binary classification on 4,601 email records
- Precision, recall, F1-score, and confusion matrix evaluation
- Comparison of multiple classifiers

---

## 🛠️ Tech Stack

| Tool | Usage |
|------|-------|
| **Python 3** | Core language |
| **Pandas & NumPy** | Data manipulation |
| **Scikit-Learn** | ML models: regression, classification, clustering |
| **Matplotlib & Seaborn** | Visualization |
| **Jupyter Notebook** | Interactive analysis environment |

---

## 💡 Key Skills Demonstrated

- ✅ Supervised learning: regression and classification
- ✅ Unsupervised learning: clustering and segmentation
- ✅ Feature engineering, selection, and transformation
- ✅ Model evaluation: accuracy, precision, recall, F1, R², RMSE
- ✅ EDA and data storytelling with Python

---

## 🚀 How to Run

```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
jupyter notebook
```

Then open any `.ipynb` file from the file browser.

---

## 📬 Author

**Janmejoy Kar** — Data Scientist | [LinkedIn](https://www.linkedin.com/in/janmejoy-kar-849756196/) | [GitHub](https://github.com/janmejoykar1807)
