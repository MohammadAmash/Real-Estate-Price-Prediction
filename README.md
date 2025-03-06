# Real-State-Price-Prediction
Project: Bangalore House Price Prediction

Developed a machine learning model to predict house prices in Bangalore using a dataset from Kaggle.
Conducted data preprocessing, including handling missing values, outlier removal, and feature engineering.
Created a new BHK feature from the size column and standardized total square feet values by handling range-based inputs.
Applied One-Hot Encoding to convert categorical location data into numerical format.
Implemented multiple regression models, including Linear Regression, Lasso Regression, and Decision Tree Regression, optimizing with Grid Search CV and K-Fold Cross Validation.
Achieved 84.5% accuracy using Linear Regression, making it the optimal model for price prediction.
Deployed the model using Flask, enabling real-time predictions via a web interface.
Saved the trained model using Pickle for efficient deployment and reuse.
Tools & Technologies: Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn, Flask.
