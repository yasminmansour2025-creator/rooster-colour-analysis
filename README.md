# Rooster Bundle & Colour Profitability Analysis

**Tools:** Python · Pandas · Scikit-learn · Matplotlib · Tableau · Jupyter  
**Context:** UTS Master of Business Analytics — Assessment 3 (2025)

## Project Overview
End-to-end analysis of e-commerce bundle performance, colour profitability,
customer loyalty, and lifetime value prediction for Rooster, a retail
clothing brand (Adam & Eve lines).

## What Was Built
- **Data Engineering:** Merged 4 datasets, reconstructed bundle cost 
  structures by mapping product-level cost schedules across two brands
- **EDA:** Colour profitability, bundle type performance, regional 
  analysis, discount impact on profit and repeat purchases  
- **Classification Models:** Logistic Regression, Decision Tree, 
  Random Forest — predicting repeat customer behaviour
- **Regression Models:** Linear Regression, Decision Tree, Random Forest 
  — forecasting customer lifetime value (CLV)
- **Model Optimisation:** GridSearchCV with stratified 5-fold 
  cross-validation on Random Forest
- **Tableau Dashboard:** Interactive story with 10+ sheets covering 
  profit potential, loyalty analysis, sensitivity scenarios, and CLV targeting

## Key Findings
- Top colour mixes identified by profit, loyalty rate, and bundle count
- Discount usage analysed against both profit margin and repeat purchase rate
- Random Forest outperformed other models on F1 and ROC-AUC for 
  repeat customer prediction

## Files
- `notebook.ipynb` — Full Python analysis
- `Rooster_Colour_Analysis.twbx` — Packaged Tableau dashboard 
  (self-contained, no external files needed)
