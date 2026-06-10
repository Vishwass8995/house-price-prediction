# 🏠 House Price Prediction

A Machine Learning regression project to predict house prices
using the Boston Housing dataset.

## 📊 Results
| Model | RMSE | R² Score |
|---|---|---|
| Linear Regression | $3.10k | 0.827 |
| Decision Tree | $3.15k | 0.822 |
| **Random Forest** | **$2.71k** | **0.868** ✅ Best |

## 🔍 Key Insights Discovered
- **luxury_score** was the #1 most important feature (score: 0.362)
  — a new feature engineered by combining avg_rooms + low_income_pct
- More rooms = higher price (correlation: 0.695)
- Higher low income % = lower price (correlation: -0.738)
- Houses near river command a **$6.3k premium** on average
- Random Forest outperformed all models with R² of 0.868

## ⚙️ Feature Engineering
Created 4 new features from scratch:
- `luxury_score` — rooms-to-income ratio (became #1 predictor!)
- `crime_distance_ratio` — safety-accessibility index
- `is_old` — binary flag for older houses
- `tax_category` — tax burden tier (low/mid/high)

## 🛠️ Tech Stack
- Python 3, Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (LinearRegression, DecisionTree, RandomForest)

## 📁 Project Steps
1. Data Loading & Exploration (EDA)
2. Outlier Detection & Removal
3. Feature Engineering (4 new features)
4. Model Building & Comparison (3 models)
5. Feature Importance Analysis

## 📂 Dataset
Boston Housing Dataset — 506 houses, 14 features

## 👤 Author
**Vishwas Sharma** — Aspiring Data Scientist
