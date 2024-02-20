# Exploratory Data Analysis of Smartphone Dataset

This Jupyter notebook performs an exploratory data analysis on the smartphone dataset (`smartphone_cleaned_v5.csv`) to understand the characteristics of the data. 

## Key Steps

- Import libraries: numpy, pandas, matplotlib, seaborn
- Load in the smartphone data
- Check shape, info, summary statistics
- Handle missing values
- Visualize distributions of key variables:
  - brand_name, model, price, rating
  - has_5g, has_nfc, processor details
  - camera, memory, display features
- Look at correlations with price and rating
- Encode categorical variables for further analysis
- Impute missing numerical values with KNN imputer
- Compare correlations before and after imputation

## Key Findings

- Price is right skewed with some high outliers
- Samsung and Apple phones are highest priced on average
- Presence of 5G and higher processor cores relate to higher price
- But higher price does not necessarily mean higher rating
- Imputation provides more robust correlations by filling gaps  
