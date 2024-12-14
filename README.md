# Credit-Card-Fraud-Detection-using-AutoEncoder

This repository contains an implementation of an anomaly detection model using a neural network. The model is designed to identify outliers or anomalies in datasets, which is crucial in fields such as fraud detection, manufacturing defect detection, and system monitoring.

## Features

- **Neural Network Model**: Implements a neural network for anomaly detection.
- **Data Preprocessing**: Includes standardization and train-test splitting.
- **Evaluation Metrics**: Generates classification reports and confusion matrices for performance evaluation.
- **Serialization**: Saves the trained model for future inference.

## Dataset

The dataset used for this project is the [Credit Card Fraud Detection dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) available on Kaggle. It contains transactions made by credit cards in September 2013 by European cardholders.

## Requirements

The project is implemented in Python and requires the following libraries:

- TensorFlow
- NumPy
- pandas
- scikit-learn
- joblib

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/Credit-Card-Fraud-Detection-using-AutoEncoder.git
   cd Credit-Card-Fraud-Detection-using-AutoEncoder
   ```

2. Run the Jupyter Notebook:

   ```bash
   jupyter notebook Anomaly_Detection_using_Neural_Network.ipynb
   ```

3. Follow the steps in the notebook to preprocess the data, train the model, and evaluate its performance.

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request for improvements.
