# Sensor Error Detection and Localization with RNNs

This notebook demonstrates how to detect, classify, and localize errors in time series data from multiple sensors using recurrent neural networks (RNNs) with Keras and TensorFlow. The workflow includes data preprocessing, model training, hyperparameter tuning, and visualization of error localization results.

## Features

- **Data Analysis & Preprocessing:**  
  - Loads and explores sensor data.
  - Handles variable-length sequences and standardizes input for modeling.

- **Modeling:**  
  - Implements and compares different RNN architectures: SimpleRNN, GRU, and LSTM.
  - Supports multi-label classification for multiple error types.
  - Uses custom callbacks for training visualization and timing.

- **Hyperparameter Tuning:**  
  - Integrates Keras Tuner for optimizing model parameters.

- **Error Localization:**  
  - Applies trained models to locate errors within sensor sequences.
  - Visualizes detected errors and their positions.

- **Visualization:**  
  - Plots sensor data, error distributions, and model predictions.

## Usage

1. **Data Preparation:**  
   Download the required data from the provided Google Drive link and place it in a `/data` folder at the root of your project.

2. **Run the Notebook:**  
   Execute the notebook step by step to preprocess data, train models, tune hyperparameters, and visualize results.

3. **Requirements:**  
   - Python 3.8+
   - TensorFlow 2.x
   - Keras
   - Keras Tuner
   - NumPy, pandas, matplotlib, scipy

4. **GPU Support:**  
   Training is faster with a GPU. If using Google Colab, ensure GPU is enabled.

## Structure

- **Section 1:** Data loading, exploration, and preprocessing.
- **Section 2:** Model definition, training, and evaluation (SimpleRNN, GRU, LSTM).
- **Section 3:** Model comparison and hyperparameter tuning.
- **Section 4:** Error localization using the best model.
- **Section 5:** Visualization of error detection and localization.

## License

This notebook is intended for educational purposes.
