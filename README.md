# Fashion-MNIST-Classification
This repository contains two examples of classifying the Fashion MNIST dataset using Keras in R and Python.

What is Fashion MNIST?

Fashion MNIST is a dataset of images of clothing items, similar to the MNIST dataset of handwritten digits. It contains 60,000 training images and 10,000 testing images, each labeled with one of 10 classes (e.g. t-shirt, trousers, etc.).

R Example

The R example uses the Keras library to load the Fashion MNIST dataset, preprocess the images, define a convolutional neural network (CNN) model, compile the model, train the model, and make predictions on two images.

Python Example

The Python example does the same thing as the R example but uses the TensorFlow and Keras libraries to load the dataset, preprocess the images, define a CNN model, compile the model, train the model, and make predictions on two images.

Steps to Classify Fashion MNIST

1. Load the Fashion MNIST dataset
2. Preprocess the images (resize and normalize)
3. Define a CNN model with several layers
4. Compile the model with an optimizer and loss function
5. Train the model on the training data
6. Make predictions on the testing data

Files in this Repository

- R code to classify Fashion MNIST
- Python code to classify Fashion MNIST

How to Run

1. Install Keras and TensorFlow in R or Python
2. Run the R or Python code in your preferred environment

Results

The trained model will be able to classify images of clothing items into one of 10 classes. The predictions made on the two images will be printed to the console.

References
1. https://www.kaggle.com/datasets/zalando-research/fashionmnist
