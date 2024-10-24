# **Sales Forecasting Using Time Series Analysis with XGBoost**

## **Project Overview** 🎯
This project aims to forecast sales for thousands of product families sold at Favorita stores using historical data. The analysis is performed using XGBoost, a powerful machine learning algorithm. Through feature engineering and model tuning, the project provides both short-term and long-term sales predictions, with a focus on generating a 30-day forecast.

## **Project Workflow** 📈

1. **Data Collection and Preprocessing**:
    - Used historical sales data provided by Favorita stores.
    - Processed the data to handle missing values and outliers.
    - Performed feature engineering to create lag features and rolling statistics.
    - Applied one-hot encoding for categorical variables and scaling for numerical variables.

2. **Exploratory Data Analysis (EDA)**:
    - Visualized sales trends over time.
    - Analyzed seasonal effects, promotions, and other external factors influencing sales.

3. **Feature Engineering**:
    - Created lag features and rolling windows to capture historical patterns.
    - Engineered calendar-related features such as day of the week, month, and promotions.

4. **Model Building**:
    - Implemented **XGBoost** for time series forecasting.
    - Fine-tuned the model using RMSE and RMSLE as evaluation metrics.
    - Generated a 30-day sales forecast.

5. **Model Evaluation**:
    - Used RMSE and RMSLE to assess the model’s accuracy.
    - Compared the model’s predictions against actual sales data for validation.

## **Key Features** 🛠️
- **XGBoost Model**: Applied an advanced machine learning approach for time series forecasting.
- **Feature Engineering**: Integrated lag and rolling statistics to enhance forecast accuracy.
- **Data Visualization**: Plots and charts to illustrate key trends and model performance.
- **30-Day Sales Forecast**: Focused on predicting future sales, with results analyzed for potential improvements.

## **Challenges & Improvements** 🔧
- **Current Challenge**: The 30-day forecast results show a linear pattern, lacking the nuanced shape of actual sales data.
- **Future Work**: Exploring advanced techniques such as model stacking, ensemble methods, and deeper time-series models (e.g., ARIMA, LSTM) to improve forecast accuracy.

## **Results** 📊
- Achieved a RMSLE of 0.409.
- Significant improvement in prediction accuracy through feature engineering.

### **Check it out on Kaggle 🔗**
You can also explore the project on Kaggle: https://www.kaggle.com/code/walidkw/store-sales-ts-forecasting-xgboost
