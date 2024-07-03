# Mnist-Image-Classification

This project aims to experiment with convolutional neural network in order to properly classify numerical values. This project specifies at exploring the learning process within a Neural Network but more importantly it aims to investigate modern deep learning libraries. Specifically in this example tensorflow.keras is being used. This project can be suitable for you wether you are a developer who needs to implement this into their project or if you are reseraching and want to see a convolutional neural network in practice.

## The Process

First we load the dataset using the load_data() function within tensorflow. Once, that is ready we divide the data into X_train, y_train, X_test, y_test. These variables will help us validate and train our model. After this, we normalize and reshape the images so that they are ready to be fed into the model. And finally we build our sequential convolutional neural network using both the ReLU and Softmax activation functions and compile the network using adam as our optimizer.
