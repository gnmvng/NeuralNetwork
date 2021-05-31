# NeuralNetwork Project - Sapienza
## DropBlock

Regularization is a technique used to reduce the errors by fitting the function appropriately on the given training set and avoid overfitting. It refers to a model that models the training data too well. Overfitting happens when a model learns the detail and noise in the training data to the extent that it negatively impacts the performance of the model on new data. This means that the noise or random fluctuations in the training data is picked up and learned as concepts by the model. The problem is that these concepts do not apply to new data and negatively impact the models ability to generalize. There have been several methodologies put forward for regularization for instance L1 and L2 regularization, Dropout, Data augmentation, Early Stopping and Data Augmentation. Although Dropout is widely used as a regularization technique for fully connected layers, it is often less effective for convolutional layers. \
We implement DropBlock according to the paper: https://arxiv.org/abs/1810.12890v1 .


Ludovico Ottobre, 1712005 \
Gianmarco Evangelista, 1711818
