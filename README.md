# Histopathologic_Cancer_Detection

In this you create an algorithm to identify metastatic cancer in small image patches taken from larger digital pathology scans.

We define the CNN model from scratch. The model type that we will be using is Sequential. Sequential is the easiest way to build a model in Keras. It allows you to build a model layer by layer.In between the Conv2D layers and the dense layer, there is a ‘Flatten’ layer. Flatten serves as a connection between the convolution and dense layers. ‘Dense’ is the layer type we will use in for our output layer. Dense is a standard layer type that is used in many cases for neural networks. 

Compiling the model takes three parameters: optimizer, loss and metrics.The optimizer controls the learning rate. We will be using ‘adam’ as our optmizer. Adam is generally a good optimizer to use for many cases. The adam optimizer adjusts the learning rate throughout training.The learning rate determines how fast the optimal weights for the model are calculated. A smaller learning rate may lead to more accurate weights (up to a certain point), but the time it takes to compute the weights will be longer.We use ‘binary_crossentropy’ for our loss function. To make things easier to interpret, we will use the ‘accuracy’ metric to see the accuracy score on the validation set when we train the model.Than we will start training our model. To train, we will use 15 number of epochs, to make. Number of epochs means the number of times you go through your training set.

This was my final project for the subject 'Applied Machine Learning'.  The dataset was used from Kaggle, can be found at 'https://www.kaggle.com/c/histopathologic-cancer-detection'. A lot of explanation I read through to understand the dataset and implement was from this post - 'https://towardsdatascience.com/histopathologic-cancer-detector-finding-cancer-cells-with-machine-learning-b77ce1ee9b0a'.

