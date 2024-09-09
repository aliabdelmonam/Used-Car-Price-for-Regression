# Machine Learning Regression Project
## Overview
-  The goal of this project is to predict the price of used cars based on various features such as brand, model, year, mileage, fuel type, transmission, and more. By analyzing historical data and training robust regression models, we can estimate car prices more accurately, the target was to get RMSE as low as possible
### 1. **Data Preprocessing**
- **Ordinal Encoding**: To handle Categorical features.
- **SimpleImputer**: Handles missing values by imputing them with the mean (for numerical features) or the most frequent value (for categorical features).
- **IsolationForest**: For detecting outlier
### 2. **Machine Learning Models**
-  **XGBoost**: An efficient and scalable gradient boosting framework.
-  **LightGBM**: A gradient boosting framework that uses tree-based learning algorithms.
###  3. Accuracy 
-  combined results between outputs from **(XGBoost, LightGBM)** using **(Mean)**
-  **RMSE** on test: 72259
## Link Notebook
-  [Kaggle Notebook](https://www.kaggle.com/code/aliabdelmenam/used-car-price-regreesion/edit/run/195853720)
-  [Kaggle competition](https://www.kaggle.com/competitions/playground-series-s4e9)
