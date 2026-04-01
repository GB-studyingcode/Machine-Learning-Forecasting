# Machine-Learning-Forecasting
**Objective:** Developed a machine learning model to accurately forecast 'units_sold' for various SKUs across multiple stores, optimizing supply chain operations.

**Key Achievements:**
*   **Data Preparation:** Transformed over 148,000 records, extracting temporal features and employing one-hot encoding for categorical variables. Managed outliers by removing instances exceeding the 99th percentile of 'units_sold'.
*   **Model Development & Optimization:** Built and refined a `RandomForestRegressor` for sales prediction.
*   **Significant Performance Improvement:** Reduced Root Mean Squared Error (RMSE) by **~37.6%** (from **28.52** to **17.80**).
*   **Hyperparameter Tuning:** Optimized model using `GridSearchCV` (best parameters: `n_estimators=200`, `min_samples_split=3`), achieving a final R-squared of **0.827** and an RMSE of **17.77**.
