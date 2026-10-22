# Car Price Prediction Using Machine Learning

## Project Overview

This project predicts the selling price of used cars using machine learning. It uses car details such as car name, manufacturing year, kilometers driven, fuel type, seller type, transmission, and ownership history.

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* CatBoost
* Matplotlib
* Google Colab
* IPyWidgets

## Machine Learning Model

CatBoost Regression is used to predict the estimated selling price of a used car.

## Model Performance

* **Mean Absolute Error (MAE):** ₹124,768.42
* **Root Mean Squared Error (RMSE):** ₹300,326.10
* **R² Score:** 0.7200

These results are from the current evaluation and may be optimistic because the test set was reused during model tuning.

## Features

* Select a car from a dropdown.
* Enter the manufacturing year and kilometers driven.
* Select fuel type, seller type, transmission, and ownership history.
* Predict the estimated selling price.

## How to Run

1. Open the project notebook in Google Colab.
2. Upload the required dataset.
3. Install the required libraries.
4. Run the notebook cells in order.
5. Enter the car details and click **Predict Price**.

## Disclaimer

The predicted price is an estimate, not a guaranteed market price.
