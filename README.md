# Predictive-Maintenance-RUL-Forecasting
Predictive Maintenance RUL Forecasting is a deep learning project aimed at forecasting the Remaining Useful Life (RUL) of industrial equipment using time series data.The project leverages advanced neural network architectures to predict when equipment is likely to fail, enabling timely maintenance and reducing unplanned downtime.
This project implements a hybrid CNN-LSTM model to analyze sensor data and predict the RUL of machinery. The model combines Convolutional Neural Networks (CNN) and Long Short-Term Memory (LSTM) networks to capture both spatial and temporal patterns in the data.
Data Preprocessing: Normalization and sequence creation from sensor readings.
Model Architecture: CNN-LSTM hybrid model with convolutional layers for feature extraction and LSTM layers for sequential learning.
Evaluation Metrics: Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R² score to assess model performance.
Failure Prediction: Identification of equipment nearing failure based on predicted RUL.
