# Ride-trip-predictor
A Machine Learning project that uses Linear Regression to analyze ride trip data and predict the target variable based on relevant trip features. The project covers data preprocessing, exploratory data analysis, feature selection, model training, evaluation, and prediction.

<img width="393" height="243" alt="Screenshot 2026-09-30 113918" src="https://github.com/user-attachments/assets/e3666180-b592-46e6-88ef-63adbe0d1c7a" />


1. Analyzed ride trip data to predict ride duration using Linear Regression.
2. Loaded and processed the ride dataset using Pandas and NumPy.
3. Converted ride start and end timestamps into datetime format and calculated ride duration in minutes.
4. Performed feature engineering by extracting start hour, day, month, and weekend information.
5. Cleaned the dataset by handling missing values, removing invalid ride durations, and filtering unrealistic rides.
6. Performed Exploratory Data Analysis (EDA) using histograms, scatter plots, KDE plots, QQ plots, hexbin plots, pairplots, and correlation heatmaps.
7. Encoded categorical variables such as Rideable Type and Member/Casual rider type for machine learning.
8. Split the dataset into 80% training and 20% testing data and built a Linear Regression model.
9. Evaluated model performance using R² Score, MAE, MSE, and RMSE, along with residual analysis.
10. Compared Linear Regression, Ridge, Lasso, and ElasticNet models and tested different train-test split sizes to analyze model performance.
