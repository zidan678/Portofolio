# Used Car Sales Analysis and Prediction

This repository contains a comprehensive analysis of a dataset sourced from [Kaggle: Mock Dataset of Second Hand Car Sales](https://www.kaggle.com/datasets/msnbehdani/mock-dataset-of-second-hand-car-sales/code) and the application of machine learning techniques to predict used car prices.

## Dataset Overview

The dataset consists of 50,000 entries with 27 features, including:

- `Engine size`: Size of the engine 
- `Year of manufacture`: Year the car was manufactured
- `Mileage`: Total distance traveled by the car 
- `Price`: Selling price of the car
- `Fuel type`: Type of fuel (Diesel, Hybrid, Petrol)
- `Model` and `Manufacturer`: Various car models and manufacturers represented as binary columns

### Correlation Analysis

The correlation matrix reveals significant relationships, such as:

- **Price and Year of Manufacture**: 0.714
- **Price and Engine Size**: 0.398
- **Price and Mileage**: -0.633

These insights indicate that newer cars and those with larger engines tend to have higher prices, while higher mileage negatively impacts car prices.

## Data Visualization

Various visualizations were created to understand the dataset better, including histograms, box plots, and scatter plots.

## Machine Learning for Price Prediction

The repository includes a Python script titled **ml_for_predict_car_prices.py**, which applies several machine learning algorithms to predict used car prices:

- **Linear Regression**
- **Decision Tree**
- **Random Forest**
- **Gradient Boosting**

### Model Performance

The results show that:

- **Linear Regression (RL)**: Performed less satisfactorily in predicting car prices compared to other models.
- **Decision Tree, Random Forest, and Gradient Boosting**: Yielded better accuracy and more reliable predictions.

## Conclusion

This repository provides a thorough analysis of used car sales data and demonstrates the application of machine learning techniques for price prediction. While Linear Regression had its limitations, the other models proved to be more effective, offering valuable insights for stakeholders in the automotive market.

---

Explore the Jupyter notebook and Python script for detailed implementations and further insights into the analysis and prediction of used car prices.
