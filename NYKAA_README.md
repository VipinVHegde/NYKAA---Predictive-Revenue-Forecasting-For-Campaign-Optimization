# Nykaa: Predictive & Revenue Forecasting for Campaign Optimization

Analysis of 55,555 digital marketing campaigns to find ROI performance gaps and predict which campaigns will succeed, using engineered KPIs and machine learning classification models.

![Python](https://img.shields.io/badge/Python-3.10%2B-blue) ![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-orange) ![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

## Problem Statement
Marketing teams spend heavily across campaign types and channels, but not every campaign pays off. This project asks: **which campaigns lose money, why, and can we predict campaign success before budget is wasted?**

## Dataset
- **Size:** 55,555 campaign records
- **Coverage:** 5 campaign types across 6 channels
- **Source:** [Add source, e.g. synthetic / Kaggle link]
- **Note:** [If the dataset is synthetic or a sample, state it here]

## Approach
1. **Data cleaning and validation:** checked missing values, data types, outliers
2. **KPI engineering:** created **CTR**, **Lead Rate** and **Conversion Rate**
3. **ROI analysis:** compared ROI by campaign type and channel to locate performance gaps
4. **Classification modelling:** built 3 ML models to predict campaign success (positive vs. negative ROI)
5. **Evaluation:** compared models using AUC-ROC and interpreted feature importance

## Key Results
| Metric | Result |
|---|---|
| Campaigns analysed | 55,555 |
| Negative-ROI campaigns | **23.8%** |
| Best model | **Decision Tree, AUC-ROC 0.965** |
| Top predictor | **Acquisition Cost** |

- Nearly one in four campaigns lost money, showing a clear opportunity for budget reallocation.
- Acquisition Cost was the strongest driver of campaign success, so cost control is the main lever for improving ROI.

> Add your charts here, e.g. `![ROC curves](images/roc_curves.png)` and `![Feature importance](images/feature_importance.png)`

## Model Comparison
| Model | AUC-ROC |
|---|---|
| Decision Tree | 0.965 |
| [Model 2] | [value] |
| [Model 3] | [value] |

## Tech Stack
Python, pandas, NumPy, scikit-learn, Matplotlib / Seaborn, Jupyter Notebook

## Repository Structure
```
nykaa-campaign-roi-prediction/
├── README.md
├── requirements.txt
├── data/            # dataset or sample
├── notebooks/       # analysis and modelling notebook(s)
├── reports/         # written report / presentation
└── images/          # charts used in this README
```

## How to Run
```bash
git clone https://github.com/<your-username>/nykaa-campaign-roi-prediction.git
cd nykaa-campaign-roi-prediction
pip install -r requirements.txt
jupyter notebook notebooks/
```

## Author
**Vipin Vijay Hegde**, MSBA
[LinkedIn](https://www.linkedin.com/in/<your-handle>) | [GitHub](https://github.com/<your-username>)
