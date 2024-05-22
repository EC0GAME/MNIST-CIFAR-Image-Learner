# MNIST-CIFAR-Image-Learner
This project is meant to indicate my ability to build convolutional and linear networks with training/test data sets. Project was built independently using PyTorch and other Python libraries.

Both segemnts of code have modifiable hyperparameters. These include: epochs, batch size, learning rate, momentum, and the log interval for softmax at the end of the network. The first network also has the ability to change which learning model the user wishes to use. Second network defaults to a convolutional network.

The first segment of the code focuses on the learning network on the MNIST dataset. 
The second segment of the code focuses on the learning network on the CIFAR10 dataset.
Each network has its own loss function for training and testing data.
Loss results are shown with percentages during each epoch throughout the runtime of the program.
