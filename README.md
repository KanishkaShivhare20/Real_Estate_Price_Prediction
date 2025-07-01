# Real_Estate_Price_Prediction - Banglore

This project is a machine learning model that predicts house prices in Bangalore based on location, number of bedrooms (BHK), and number of bathrooms.

## Technologies Used:
  • Python  
  • Pandas  
  • NumPy  
  • Scikit-learn  
  • Matplotlib  
  • Pickle  
  • JSON

## 📂 Project Structure
  • banglore_home_prices_model.pickle – Trained ML model  
  • columns.json – List of features used in training  
  • pricePrediction.ipynb – Jupyter Notebook with full code  
  • README.md – Project documentation (this file)

## 📊 Main Features Used for Prediction
  • Total square feet (sqft)  
  • Number of bathrooms  
  • Number of bedrooms (BHK)  
  • Location (converted to one-hot encoded columns)

## 🔄 Steps Followed
  1. Data loading and cleaning  
  2. Feature engineering (like extracting BHK from size)  
  3. Outlier detection and removal  
  4. One-hot encoding of location column  
  5. Model training using Linear Regression, Lasso, and Decision Tree  
  6. Cross-validation with ShuffleSplit and GridSearchCV  
  7. Saving model and columns for future predictions
