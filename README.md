# AI Project: Traffic Flow Prediction using LSTM

This project focuses on time series forecasting using a Long Short-Term Memory (LSTM) neural network to predict traffic flow. The dataset used contains hourly traffic counts, which are preprocessed, visualized, and then used to train a deep learning model. The workflow includes:

- Structuring data into sequences for LSTM input
- Building and training an LSTM model using TensorFlow and Keras
- Evaluating model accuracy using performance metrics
- Visualizing predictions to assess effectiveness

## Prediction Methodology
- The dataset consists of historical traffic flow data recorded at hourly intervals.
- Data is cleaned, missing values are handled, and values are normalized using MinMax scaling to ensure stable model training.
- A sliding window approach is used to create input sequences, where past traffic data points are fed into the model to predict future traffic counts.
- The LSTM model, built using TensorFlow and Keras, captures temporal dependencies in traffic patterns through its recurrent layers.
- The model is trained using historical traffic trends and optimized using Mean Squared Error (MSE) to minimize prediction errors.
- Once trained, the model predicts upcoming traffic counts, which are compared with actual values to validate accuracy.
- The results are visualized using time series plots to show predicted vs. actual traffic trends, helping in traffic congestion forecasting and urban mobility planning.

