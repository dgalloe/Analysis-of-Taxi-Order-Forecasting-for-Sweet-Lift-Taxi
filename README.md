# Analysis-of-Taxi-Order-Forecasting-for-Sweet-Lift-Taxi
Analyzed historical taxi order data from airports to predict hourly demand during peak periods. Built time series forecasting models to optimize driver allocation and improve service efficiency. Provided actionable insights for operational planning and revenue maximization.

## 1. Objectives 🎯
- Develop predictive models for hourly taxi order demand at airports
- Achieve RMSE below 48 on test data as project requirement
- Analyze time series patterns and seasonal trends in taxi orders
- Implement and compare multiple regression models with hyperparameter tuning
- Prepare data through resampling and feature engineering for time series forecasting

## 2. Key Findings 🏆
- Successfully implemented multiple forecasting models including Linear Regression, XGBoost, and LightGBM
- Achieved target RMSE metric through appropriate feature engineering and model optimization
- Identified clear daily and weekly patterns in taxi order demand
- Demonstrated the importance of lag features and rolling averages for time series prediction
- Established robust data preprocessing pipeline ensuring chronological consistency and data quality

## 3. Visualizations Included 🎨
- Time series plot of hourly taxi orders showing clear demand patterns
- Seasonal decomposition analysis revealing trend and cyclical components
- Model performance comparison across different algorithms
- Feature importance analysis for optimal model selection
- Residual analysis and error distribution visualization

## 4. Skills Demonstrated 🛠️
- Time Series Analysis: Resampling, trend analysis, seasonal pattern identification
- Feature Engineering: Creation of calendar features, lag variables, rolling statistics
- Machine Learning: Implementation of multiple regression models (Linear, XGBoost, LightGBM)
- Model Evaluation: RMSE calculation, hyperparameter optimization, train-test splitting
- Data Visualization: Time series plotting, model performance comparison
- Statistical Analysis: Seasonal decomposition, trend identification
- Python Programming: pandas for data manipulation, scikit-learn for modeling, matplotlib for visualization

## 5. Technical Details 💻
- Programming Language: Python
- Main Libraries: pandas, matplotlib, sklearn, LightGBM, XGBoost, statsmodels
- Dataset: 26,496 time-stamped taxi orders from airports (March-August 2018)
- Time Resolution: Resampled to hourly intervals for consistent forecasting
- Feature Engineering: Created 24 lag features, rolling mean (24h), and calendar features (year, month, day, weekday, hour)
- Model Evaluation: RMSE metric with 10% test split validation
- Key Models: Linear Regression, XGBRegressor, LGBMRegressor

## 6. Installation and Usage
```bash
# Clone the repository
git clone https://github.com/yourusername/taxi-order-forecasting.git

# Navigate to project directory
cd taxi-order-forecasting

# Install required dependencies
pip install -r requirements.txt

# Run the analysis notebook
jupyter notebook taxi_order_forecasting.ipynb
