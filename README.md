# Mnist-Dataset-Hyperparameter-Tuning

Hyperparameter tuning by experimenting with various model architectures and configurations on the MNIST dataset. I've built 5 models, each with different configurations:

Model 1: A basic neural network with no hidden layers, using softmax activation for classification and achieving around 93% accuracy.

Model 2: Added a hidden layer with 32 units and relu activation, improving performance to around 97% accuracy.

Model 3: Adjusted the learning rate to 0.0001, achieving around 94% accuracy.

Model 4: Increased the number of hidden units to 128 and stacked two hidden layers, reaching about 97.8% accuracy.

Model 5: Added regularization with L2 and Dropout layers to prevent overfitting, also performing well with over 96% validation accuracy

Each of these models shows progressive improvement in architecture, learning rates, and regularization.
