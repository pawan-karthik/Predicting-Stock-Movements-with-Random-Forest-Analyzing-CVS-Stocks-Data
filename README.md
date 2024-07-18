# Predicting Stock Movements with Random Forest: Analyzing CVS Stocks Data

## Overview
This project involves developing a machine learning model to predict stock price movements for CVS Health Corporation using historical stock data. The model leverages the Random Forest algorithm to capture complex patterns and dependencies in the data.

## Project Structure
### Data Preprocessing: Handling missing values, scaling features, and splitting the data into training and testing sets.
### Feature Engineering: Creating lagged features to capture temporal dependencies in the stock price data.
### Model Training: Training a Random Forest regression model to predict future stock prices.
### Evaluation: Assessing model performance using metrics such as Mean Absolute Error (MAE) and R-squared (R²), along with classification metrics including Precision, Accuracy, Recall, and F1 Score.

## Dataset Details
Historical CVS Health Stock Data
### Description: This dataset contains historical stock data for CVS Health, including daily opening and closing prices, highest and lowest prices of the day, adjusted closing prices, and trading volume.
Time Period: Daily stock prices and volume from February 22, 1973.

Usability: 10.00
License: CC0: Public Domain
Expected Update Frequency: Weekly

## Key Results
### Classification Metrics:
Precision: 0.51
Accuracy: 0.49
Recall: 0.50
F1 Score: 0.50

The prediction plot shows that the model effectively captures the overall trend of stock movements, despite some deviations.

## Future Work
To further improve the model's performance, consider the following steps:

#### Feature Selection: Incorporate additional features such as trading volume, technical indicators, and macroeconomic variables.
#### Model Tuning: Adjust hyperparameters of the current model or experiment with advanced models like Long Short-Term Memory (LSTM) networks or Gradient Boosting Machines.
#### Ensemble Methods: Combine predictions from multiple models to reduce variance and enhance robustness.

### Installation and Usage
Clone the Repository:

(Copy code)
git clone https://github.com/pawan-karthik/Predicting-Stock-Movements-with-Random-Forest-Analyzing-CVS-Stocks-Data.git


## Conclusion
This project demonstrates the application of the Random Forest algorithm to predict stock price movements. The results indicate a reasonable level of accuracy and provide a solid foundation for further enhancements.

For more details, please refer to the attached Jupyter notebook.
