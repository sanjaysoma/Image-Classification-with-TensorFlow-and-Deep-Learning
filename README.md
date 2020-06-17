# Image-Classification-with-TensorFlow-and-Deep-Learning
This project uses TensorFlow and deep learning models to classify multi-class images. Throughout the project, different models are presented to make better predictions step by step:

1, defines a delta function calculating the difference between the RGB components, and classify the image to the class with the smallest RGB difference;

2, rather than compare RGB difference to all images in a class, for each class, I generate a typical image that minimizes the RGB difference to all training images in this class using gradient descent; and only compare images in test set to typical images for each class;

3, customize a logistic regression model to make multi class classifications using softmax model;

4, build a multi-layer fully-connected neural network that takes the pixel values as input and yields a class prediction as output;

5, build a neural network with convolutional layers to improve the performance, with two convolutional layers and two fully-connected layers, using AdamOptimizer;

6, load a pretrained interception network model, transform all train and test images into latent vectors, and make prediction with a fully-connected neural network model based on the latent vectors. 
