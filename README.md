# csci323-dubai-realestate-ai
AI-powered Dubai real estate transaction price prediction using Machine Learning — CSCI323 Modern AI Project | University of Wollongong Dubai

# Dubai Real Estate Transaction Price Prediction
### CSCI323 — Modern Artificial Intelligence | Spring 2026
**University of Wollongong Dubai (UOWD)**

---

## Project Overview
An end-to-end machine learning pipeline that predicts Dubai property transaction prices using real data from the Dubai Land Department (DLD). The project applies regression, classification, and clustering techniques to provide data-driven property valuation insights.

---

## Dataset
The dataset is sourced from [DubaiPulse](https://www.dubaipulse.gov.ae) — Dubai Land Department Real Estate Transactions.

📁 **Download transactions.csv here:** https://drive.google.com/file/d/1vXX4OD6jubIUnrRKwpQgKkV5wfsz19pv/view?usp=sharing

After downloading, place the file in the `data/` folder: 
data/transactions.csv

---

## Notebooks — Run in Order
| # | Notebook | Description | Member |
|---|----------|-------------|--------|
| 01 | `01_data_eda.ipynb` | Data cleaning and exploratory data analysis | Member 1 |
| 02 | `02_preprocessing_baseline.ipynb` | Preprocessing pipeline and baseline models | Member 2 |
| 03 | `03_random_forest.ipynb` | Random Forest regression and classification | Member 3 |
| 04 | `04_ann_model.ipynb` | ANN with Keras Tuner and model comparison | Member 4 |
| 05 | `05_clustering_evaluation.ipynb` | KMeans clustering and market segmentation | Member 5 |

---

## Installation
```bash
pip install pandas numpy matplotlib seaborn scikit-learn tensorflow keras-tuner yellowbrick
```

---

## Team
| Member | Role |
|--------|------|
| Amir Hossein Torkaman | Data Lead, EDA, GitHub Owner |
| Member 2 | Preprocessing + Baseline Models |
| Member 3 | Random Forest |
| Member 4 | ANN + Model Comparison |
| Member 5 | Clustering + Conclusion |
