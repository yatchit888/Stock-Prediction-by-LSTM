The `LSTM_Stock_prediction` project is a machine learning application that uses Long Short-Term Memory (LSTM), a type of recurrent neural network, to predict stock prices. The project specifically uses the daily opening price data of Maotai's stock. The LSTM model is trained on a sequence of 60 consecutive days of opening prices to predict the opening price of the 61st day.

The project uses several Python libraries:

- `tensorflow` for building and training the LSTM model
- `matplotlib` for data visualization
- `pandas` for data manipulation and analysis
- `numpy` for numerical computations
- `sklearn` for data preprocessing and performance metrics

The project also uses dropout and dense layers from Keras, which is now a part of TensorFlow. Dropout is a regularization technique for reducing overfitting, and dense layers are the regular deeply connected neural network layers.

The performance of the model is evaluated using metrics from `sklearn`, specifically mean squared error and mean absolute error. These metrics provide a quantitative measure of the model's prediction accuracy.
