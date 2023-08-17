# Detecting-depression-using-tweets

cnn_accuracy = model.evaluate(x_data, y_data, verbose=0)[1]
print("CNN Model Accuracy:", cnn_accuracy)


lstm_accuracy = model.evaluate(x_data, y_data, verbose=0)[1]
print("LSTM Model Accuracy:", lstm_accuracy)
