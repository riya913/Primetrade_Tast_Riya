# Trader Performance & Market Sentiment Analysis

This project explores the relationship between trader performance and market sentiment using transaction data and sentiment indices. It includes data cleaning, exploratory data analysis (EDA), feature engineering, and classification modeling to predict market sentiment based on trading patterns.

## Project Overview

- **Objective:**  
  To analyze how trader performance correlates with market sentiment and build predictive models that classify market sentiment using trading data.

- **Datasets:**  
  - Trader transactions data (2024)  
  - Market sentiment data (Fear & Greed Index from 2018 to 2024)

- **Approach:**  
  - Data preprocessing and cleaning  
  - Feature engineering including encoding categorical variables  
  - Exploratory data analysis (visualizations, distributions, correlations)  
  - Building and evaluating classification models (Logistic Regression, Random Forest, XGBoost)  
  - Model validation and interpretation

## File Structure

- `fear_greed_index.csv` — Market sentiment data containing daily Fear & Greed scores  
- `trader_data.csv` — Trader transaction data for 2024  
- `Trader_Sentiment_Analysis.ipynb` — Jupyter notebook with full analysis, EDA, modeling, and results  

## Key Steps & Highlights

1. **Data Loading & Cleaning:**  
   Handled missing data, aligned timestamps between datasets, and filtered relevant records.

2. **Feature Engineering:**  
   Encoded categorical variables such as `Side` and `Direction`, and created binary target labels.

3. **Exploratory Data Analysis:**  
   Visualized distributions of key numeric features, classification label distributions, and relationships via scatterplots.

4. **Modeling:**  
   Implemented multiple classification algorithms with train-test splits and cross-validation.  
   Achieved high accuracy (~99%) in predicting market sentiment categories.

5. **Model Interpretation:**  
   Analyzed feature importances and classification reports to evaluate model strengths.

## How to Run

1. Clone the repository.  
2. Place the CSV data files in the working directory.  
3. Open the Jupyter notebook `Trader_Sentiment_Analysis.ipynb`.  
4. Run cells sequentially to reproduce the analysis and results.

## Dependencies

- Python 3.8+  
- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn  
- xgboost

You can install required packages using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost
