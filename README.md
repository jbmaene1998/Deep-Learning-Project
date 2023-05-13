# Deep-Learning-Project


This GitHub repository contains code for a text classification model that uses a recurrent neural network (RNN) to classify song lyrics into two classes. The code is written in Python and uses the TensorFlow and Keras libraries. The model is trained on a dataset of song lyrics and their associated labels, and is then used to make predictions on a test set of lyrics.

The code begins by importing the necessary libraries and reading in the training data from a CSV file. The lyrics and labels are then separated into separate arrays. A tokenizer object is created and fit on the lyrics, and the lyrics are converted to sequences of integers using the tokenizer. The sequences are then padded with zeros to ensure that they are all the same length.

The preprocessed data is split into training and validation sets using the train_test_split function from scikit-learn. The RNN model is then built using the Keras Sequential API, with an embedding layer, an LSTM layer, and a dense output layer. The model is compiled with an optimizer and a loss function, and is then trained on the training set using the fit method.

The model is then evaluated on the test set using the evaluate method, and the training and validation loss and accuracy are plotted using Matplotlib. Finally, the model is used to make predictions on a separate test set of lyrics, and the predictions are saved to a CSV file.

Overall, this GitHub repository provides a complete and well-documented example of how to build and train a text classification model using an RNN and Keras. It can be used as a starting point for similar projects in natural language processing and machine learning.
