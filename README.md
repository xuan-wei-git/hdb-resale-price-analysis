# HDB Resale Price Analysis & Prediction

## Overview
This project analyses Singapore HDB resale transactions to uncover key factors influencing housing prices and build machine learning models to predict resale prices.

## Dataset
- Source: data.gov.sg (Resale Flat Prices) (2012- 2026)
- Size: ~100K+ records
- Features: month, town, flat_type, block, street_name, storey_range, floor_area_sqm, flat_model, lease_commence_date, remaining_lease, resale_price

## Key Steps
- Data cleaning, preprocessing and validation
- Feature engineering (lease years conversion, storey midpoint)
- Exploratory Data Analysis (EDA)
- Model building (Logistic Regression, Clustering, Linear Regression, Random Forest)
- Time-series cross-validation

## Key Insights
- Resale price dropped to lowest in 2019 before rising significantly in 2020 to 2026
- Although the dummy variables with the top 10 absolute coefficient values mostly belong to flat type and flat model, when grouped together, it is town which has the greatest importance followed by flat model then flat type
- From price classification, I can see that town and flat model are the main features that affects whether the resale price is classified as low, medium or high. Although the accuracy is only 0.393
- Random Forest improved RMSE by ~XX% over baseline
- Segmented market into X clusters

## Models
- Logistic Regression
- Clustering
- Linear Regression
- Random Forest

## Sample Outputs

## Tools Used
- Python (Pandas, Numpy, Scikit-learn, Matplotlib)
