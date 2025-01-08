# House Price Prediction Project

*Problem Statement:
   The goal of this project is to predict house prices using a dataset of housing features and prices. By applying data preprocessing, exploratory data analysis (EDA), and machine learning models, we aim to build a robust predictive model that can accurately estimate house prices based on input features.

*Libraries Used:

  pandas: Data manipulation and analysis
  numpy: Numerical computations
  matplotlib: Data visualization
  seaborn: Statistical data visualization
  sklearn:
      ->Model building and evaluation (Linear Regression, Random Forest, Decision Tree, Gradient Boosting)
      ->Preprocessing (LabelEncoder, MinMaxScaler)
      ->Metrics (MAE, MSE, RMSE, R-squared)
  scipy: Statistical computations (skewness and kurtosis)

*Project Steps:

 Step1: Data Preprocessing: Handled missing values, converted date column to datetime format, and removed high-cardinality features.
    
 Step2: Exploratory Data Analysis: Visualized relationships between features and the target variable using box plots and calculated statistical distributions.
    
 Step3: Feature Engineering: Encoded categorical features, removed outliers, normalized numeric data, and identified relevant features using correlation analysis.
    
 Step4: Model Training and Evaluation: Trained multiple regression models (Linear Regression, Random Forest, Decision Tree, Gradient Boosting) and compared performance                 		       metrics to select the best model (Random Forest in this case).

*Additional Information:

   Code Reference: The project implementation code is provided in the attached Python script (house_price_prediction.py).
   Visualization: The project includes detailed plots, such as box plots and correlation heatmaps, to aid in understanding the dataset and model predictions.
