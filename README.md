# Housing Price Predictor

This project is a machine learning-based system to predict housing prices based on various input features.

## Features

- Predict housing prices based on input parameters such as square footage, location, and number of bedrooms.
- Uses machine learning algorithms like Linear Regression for prediction.
- Handles missing data using imputation techniques.
- Implements feature scaling and normalization for improving model accuracy.
- Evaluates model performance using metrics such as Mean Absolute Error (MAE) and Root Mean Square Error (RMSE).

## Algorithms and Techniques Used

- **Linear Regression**: A basic supervised learning algorithm used for predicting continuous values.
- **Data Preprocessing**: Includes handling missing values, feature scaling, and normalization.
- **Model Evaluation**: Uses metrics like MAE and RMSE to evaluate the performance of the prediction model.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/housing-price-predictor.git

2. Install required dependencies:
pip install -r requirements.txt

3.Run the Jupyter notebook housing_price_predictor.ipynb:
jupyter notebook housing_price_predictor.ipynb


## Dataset

The dataset contains various features of houses like:

- Number of bedrooms
- Size in square feet
- Location
- Number of bathrooms

These features are used to predict the final selling price of a house.

## Dependencies

- Python 3.x
- Pandas
- Scikit-learn
- NumPy
- Matplotlib

## Results

The model provides accurate predictions for housing prices, with the final evaluation metrics showing good generalization to the validation set.

