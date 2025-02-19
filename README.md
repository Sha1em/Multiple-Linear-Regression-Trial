# Multiple-Linear-Regression-Trial
Multiple Linear Regression on Car Horsepower Prediction 🚗💨

This project explores predicting car engine horsepower using multiple linear regression with feature engineering, outlier handling, and multicollinearity analysis. The dataset used comes from the Corgis Cars dataset, and the workflow involves data cleaning, feature selection, scaling, regression modeling, and evaluation.

Key Steps in the Analysis:
✅ Feature Selection: Chose Engine Displacement and City MPG as independent variables based on correlation analysis.
✅ Outlier Handling: Applied the IQR (Interquartile Range) method to remove extreme values for a cleaner dataset.
✅ Feature Scaling: Standardized selected features using StandardScaler to ensure consistent weightage in regression.
✅ Multicollinearity Check: Calculated Variance Inflation Factor (VIF) to ensure minimal collinearity between predictors.
✅ Model Training & Evaluation: Trained a Multiple Linear Regression model and evaluated it using MSE (Mean Squared Error) and R² Score to assess its predictive power.
✅ Visualization: Plotted actual vs. predicted horsepower values with an identity line to analyze model performance.

Performance Metrics:
📉 MSE: [Your computed MSE]
📈 R² Score: [Your computed R²]

This project highlights the power of data preprocessing and feature engineering in building a reliable regression model. The insights gained here can be extended to more complex predictive modeling tasks in the automotive domain.

🚀 Check out the full code in this repository and feel free to contribute or improve upon it!
