# HDB Resale Price Analysis & Prediction

## Overview
This project analyses HDB resale transactions to identify key price drivers and build predictive models for resale prices.

## Dataset
- Source: Data.gov.sg (HDB resale data)
- Size: ~100K+ records
- Features: Town, flat type, floor area, lease, resale price

## Key Steps
- Data cleaning and validation
- Feature engineering (lease conversion, storey midpoint)
- Exploratory Data Analysis (EDA)
- Model building (Linear Regression, Random Forest)
- Time-series cross-validation

## Results
- Identified key drivers: floor area, lease, flat type
- Random Forest improved RMSE by ~XX% over baseline
- Segmented market into X clusters

## Tools Used
- Python (Pandas, Scikit-learn, Matplotlib)

## How to Run
```bash
pip install -r requirements.txt
