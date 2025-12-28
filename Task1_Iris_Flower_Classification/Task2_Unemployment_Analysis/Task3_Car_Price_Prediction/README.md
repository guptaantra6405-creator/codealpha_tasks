# Car Price Prediction with Machine Learning

This project is completed as part of the CodeAlpha Data Science Internship.

## Objective
To build a machine learning regression model that predicts car selling prices based on vehicle features such as year, mileage, fuel type, transmission, and ownership.

## Dataset
The dataset is sourced from Kaggle and contains information about used cars, including:
- Year
- Present Price
- Kilometers Driven
- Fuel Type
- Seller Type
- Transmission
- Owner
- Selling Price (Target)

## Methodology
- Data loading and inspection
- Data cleaning and preprocessing
- One-hot encoding of categorical features
- Model training using Linear Regression and Random Forest Regressor
- Model evaluation using MAE, RMSE, and R² score
- Feature importance analysis
- Visualization of actual vs predicted prices

## Model Performance
- Linear Regression R² Score: ~0.85
- Random Forest R² Score: ~0.96

## Key Insights
- Car showroom price and year strongly influence resale value.
- Higher mileage reduces selling price.
- Diesel cars generally have higher resale value.
- Random Forest outperforms Linear Regression due to non-linear relationships.

## Tools & Technologies
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Conclusion
This project demonstrates the application of machine learning regression techniques for real-world car price prediction, supporting data-driven decision-making.

## Author
Antra Gupta
