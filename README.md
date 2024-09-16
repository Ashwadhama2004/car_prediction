# car_prediction
Here's a `README.md` file including the MIT License reference:

```markdown
# Car Price Prediction

This project is a machine learning model for predicting the selling price of used cars. The model uses a dataset from Car Dekho and applies various regression techniques such as Random Forest Regressor and Lasso Regression to predict car prices based on features such as year, kilometers driven, fuel type, and more.

## Features

- **Data Preprocessing**: The dataset is cleaned and preprocessed, including encoding categorical variables like fuel type, seller type, transmission, and ownership.
- **Modeling**: Two machine learning models are used:
  - **Random Forest Regressor**: Achieves a training R² score of 0.96 and a test R² score of 0.86.
  - **Lasso Regression**: Achieves a training R² score of 0.42 and a test R² score of 0.49.
- **Prediction**: The model can predict the price of a car based on inputs such as year, kilometers driven, fuel type, and ownership history.

## Dataset

The dataset contains 4,340 rows with the following columns:
- `name`: Name of the car.
- `year`: Year of manufacture.
- `selling_price`: The selling price of the car (target variable).
- `km_driven`: Number of kilometers the car has been driven.
- `fuel`: Type of fuel used (Petrol, Diesel, etc.).
- `seller_type`: Type of seller (Individual, Dealer, etc.).
- `transmission`: Type of transmission (Manual, Automatic).
- `owner`: Ownership history (First Owner, Second Owner, etc.).

## Libraries Used

- `pandas`: For data manipulation and analysis.
- `numpy`: For numerical operations.
- `scikit-learn`: For machine learning models, including Random Forest and Lasso.
- `seaborn` and `matplotlib`: For data visualization.
  
## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/Ashwadhama2004/car-price-prediction.git
   cd car-price-prediction
   ```

2. Install the required Python packages:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter notebook or Python script to train the model and make predictions.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
```

https://github.com/Ashwadhama2004/car-price-prediction.git 
