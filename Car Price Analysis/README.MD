# Used Car Sales Analysis

This repository contains an analysis of a dataset sourced from [Kaggle: Mock Dataset of Second Hand Car Sales](https://www.kaggle.com/datasets/msnbehdani/mock-dataset-of-second-hand-car-sales/code). The analysis is conducted in the Jupyter Notebook titled **Analysis of Used Car Prices.ipynb**, which explores a dataset of 50,000 used car sales.

## Key Features

- `Engine size`: Size of the engine (in liters)
- `Year of manufacture`: Year the car was manufactured
- `Mileage`: Total distance traveled by the car (in kilometers)
- `Price`: Selling price of the car
- `Fuel type`: Type of fuel (Diesel, Hybrid, Petrol)
- `Model` and `Manufacturer`: Various car models and manufacturers represented as binary columns

## Correlation Analysis

The correlation matrix reveals significant relationships:

- **Price and Year of Manufacture**: 0.714
- **Price and Engine Size**: 0.398
- **Price and Mileage**: -0.633

## Data Visualization

Various visualizations were created to understand the dataset, including:

- Histograms
- Box plots
- Scatter plots

## Machine Learning Model

Using a Decision Tree model, the following features were identified as important for predicting car prices:

| Feature                  | Importance Score |
|--------------------------|------------------|
| Year of manufacture       | 0.623356         |
| Engine size               | 0.263347         |
| Mileage                   | 0.033350         |
| Model_M5                  | 0.022855         |
| Model_911                 | 0.019586         |

## Conclusion

This analysis provides valuable insights into the factors influencing used car prices, beneficial for buyers, sellers, and manufacturers.

---

Explore the Jupyter notebook for detailed analysis and visualizations.
