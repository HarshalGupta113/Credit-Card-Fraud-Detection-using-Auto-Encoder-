# Credit-Card-Fraud-Detection-using-Auto-Encoder-

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
   git clone https://github.com/yourusername/anomaly-detection-neural-network.git
   cd anomaly-detection-neural-network
   ```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter Notebook:

   ```bash
   jupyter notebook Anomaly_Detection_using_Neural_Network.ipynb
   ```

4. Follow the steps in the notebook to preprocess the data, train the model, and evaluate its performance.

## File Structure

- **Anomaly_Detection_using_Neural_Network.ipynb**: Main notebook containing the implementation.
- **requirements.txt**: List of dependencies.
- **model/**: Directory to save the trained model.

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request for improvements.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

Special thanks to the open-source community for providing the tools and libraries used in this project.


