# -Stock-Market-Prediction-and-Forecasting-Using-Stacked-LSTM-
This project implements a Long Short-Term Memory (LSTM) neural network to predict stock prices based on historical stock data. 

Project Workflow:
1-Data Preprocessing:
Missing data checks were performed, and it was found that there were no missing values.
The Close price was extracted and visualized using Matplotlib then was scaled using the MinMaxScaler to ensure all values are in the range [0, 1].
The data was split into training (70%) and testing sets (30%).

2-LSTM Model Architecture and training:
A stacked LSTM model with three LSTM layers (each with 50 units) was created.
The model was compiled with the Adam optimizer and the mean squared error (MSE) loss function.
The model was trained for 100 epochs with a batch size of 64.

3-Evaluation:
After training, the model achieved good performance with validation loss converging to a low value.
The model is ready to predict future stock prices based on the given data.

Libraries Used:
Numpy: For numerical operations.
Pandas: For data loading and preprocessing.
Matplotlib & Seaborn: For data visualization.
Scikit-Learn: For data scaling and evaluation.
TensorFlow/Keras: For building the LSTM neural network.
