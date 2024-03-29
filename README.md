# Stock Market Prediction using Artificial Neural Networks (ANN)

This repository contains Python code for predicting stock market prices using Artificial Neural Networks (ANN). The code utilizes Keras for building and training the neural network model.

## Introduction

Predicting stock prices is a challenging task due to the unpredictable nature of financial markets. However, Artificial Neural Networks (ANN) have shown promise in capturing patterns and trends in stock market data, making them suitable for prediction tasks.

## Requirements

- Python (>=3.5)
- Keras (>=2.0)
- Pandas
- NumPy
- Matplotlib

## Usage

1. Clone the repository:

    ```bash
    git clone https://github.com/Arunjagan12/stock-market-prediction-using-ann.git
    cd stock-market-prediction
    ```

## Dataset

The dataset used in this project is provided in the CSV file `EDELWEISSNS.csv`. It contains historical stock market data including Open, High, Low, Close, and Volume. The data is preprocessed to handle missing values and normalize features before training the ANN model.

## Model Architecture

The neural network model used for stock market prediction consists of multiple dense layers with ReLU activation functions. The model is trained using the Adam optimizer and mean squared error (MSE) loss function.

## Results

After training the model, predictions are made on test data, and the performance of the model is evaluated using MSE and RMSE metrics. Additionally, the predicted values are plotted against the actual stock prices to visualize the model's performance.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
