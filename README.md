# Life Expectancy Prediction Challenge

## 📌 Project Overview
Developed a machine learning pipeline to predict life expectancy based on socioeconomic indicators. This project was completed as part of a Data Science hiring assessment.

## 🛠️ Technical Highlights
- **Feature Engineering:** Resolved unit inconsistencies (km² vs hectares) and created normalized land-use ratios.
- **Data Cleaning:** Implemented regex-based parsing for complex string features (e.g., "internet users per 1000").
- **Imputation:** Used **IterativeImputer** (MICE) to handle missing values based on economic correlations.
- **Model:** Tuned **XGBoost Regressor** with **RandomizedSearchCV**.
- **Validation:** Utilized **GroupKFold** to prevent spatial data leakage between geographical regions.