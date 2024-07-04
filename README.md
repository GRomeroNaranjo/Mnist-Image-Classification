
# Mnist Image Classification

The goal is by using a highly known deep learning dataset we can correctly configure an architecture which is streamlined and optimized to delivering accuracte predictions for digit recognition. While using modern day libraries we can efficiently train our model using a Convolutional Neural Network. 

## The Process

First we load the dataset using the load_data() function within tensorflow. Once, that is ready we divide the data into X_train, y_train, X_test, y_test. These variables will help us validate and train our model. After this, we normalize and reshape the images so that they are ready to be fed into the model. And finally we build our sequential convolutional neural network using the ReLU, Softmax activation functions and using adam as our optimizer.
