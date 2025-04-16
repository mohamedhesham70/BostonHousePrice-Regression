# BostonHousePrice-Regression
🏡 Boston House Price Prediction Project

Tools Used: Python, Pandas, Seaborn, Matplotlib, Scikit-learn, XGBoost
Project Type: Regression (Supervised Machine Learning)

Objective:
Predict housing prices in the city of Boston based on a range of demographic and social features using various machine learning models.

Steps & Highlights:

✅ Data Preprocessing:

Imported the dataset from a CSV file.

Removed unnecessary columns.

Checked and confirmed there were no missing values.

Applied Normalization and Standardization according to model requirements.

📊 Exploratory Data Analysis (EDA):

Performed statistical analysis using .describe() and .info().

Created a correlation heatmap to understand feature relationships.

Plotted distribution graphs for all features.

Analyzed the relationship between number of rooms, income level, and house prices.

🔍 Modeling:

Linear Regression:

Used normalized data.

Results: R² = 0.67, MSE = 24.29

Random Forest Regressor:

Used standardized data.

Results: R² = 0.89, MSE = 7.84

XGBoost Regressor:

Used standardized data.

Results: R² = 0.91, MSE = 6.42

Conclusion:
Three models were compared, and XGBoost outperformed the others in prediction accuracy. This highlights the importance of selecting the right model based on the nature of the data and the problem.
