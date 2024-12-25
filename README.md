# ANN
A neural network for regression involving a definite model with appropriate layers and parameters tailored to the regression task.
Building a neural network to train a regression data.
The steps are as follows:
  - Encoded some columns in the diamonds.csv dataset.
  - Splited and trained the data from sklearn.model_selection using the train_test_split function.
  - Using the Sequential model from keras, i fitted the input layer, two hidden layers, a drop out to prevent overfitting and improve the model's generalization and an output layer
  - Compiled the model, saved the model[best] and fitted the model on the trained data.
  - Evaluated the data to determine the loss and Errors(mean square error and mean absolute error)
