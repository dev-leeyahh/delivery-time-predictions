### Version 1 – Baseline Model
- Single and two-feature linear regression
- No feature engineering
- Higher RMSE

### Version 2 – Improved Model
- Feature engineering (interaction & squared terms)
- Feature scaling (standardization)
- Learning rate tuning
- Significantly reduced RMSE

# Food Delivery Time Prediction

This project trains a linear regression model to predict food delivery time based on
order distance, preparation time, and traffic conditions.

## Problem Statement
Accurate delivery time prediction is important for customer satisfaction in food
delivery platforms. This project explores how machine learning can be used to model
delivery time using real-world inspired features.

## Features Used
- ORDER_DISTANCE
- PREP_TIME
- TRAFFIC_INDEX
- Engineered features:
  - DISTANCE × TRAFFIC
  - PREP_TIME × TRAFFIC
  - DISTANCE²
  - TRAFFIC²

## Model
- Linear Regression
- Feature scaling using Standardization
- Evaluation metric: RMSE

## Results
- Feature engineering significantly reduced RMSE
- Higher learning rates were effective after standardization

## Tools & Libraries
- Python
- Pandas
- NumPy
- TensorFlow / Keras
- Scikit-learn
- Matplotlib

## How to Run
1. Clone the repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
