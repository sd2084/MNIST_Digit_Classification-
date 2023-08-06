# MNIST_Digit_Classification
**Introduction:**

Welcome to the MNIST Digit Classification project! This repository contains a simple image classification model built using the MNIST dataset of handwritten digits. The code is implemented in Python using TensorFlow and Keras.
The goal of this project is to provide a basic example of image classification using a feedforward neural network. Users can understand how to load data, preprocess it, build a neural network, train the model, and evaluate its performance on the test set.

**The script will perform the following steps:**
1. Load the MNIST dataset: The code will automatically download the MNIST dataset, which contains 28x28 grayscale images of handwritten digits and their corresponding labels.
2. Preprocess the data: The pixel values of the images are normalized to the range [0, 1] to improve training efficiency. The images are also flattened from 28x28 to a 1D array of length 784 to be used as input for the neural network.
3. Build the Neural Network: A simple feedforward neural network is constructed using TensorFlow's Keras library. It consists of a hidden layer with 128 neurons and a ReLU activation function, followed by an output layer with 10 neurons and a softmax activation function.
4. Compile the Model: The model is compiled with the categorical cross-entropy loss function for multi-class classification. The Adam optimizer is used for training, and the evaluation metric is set to accuracy.
5. One-hot Encode the Labels: The integer labels (0 to 9) are converted to one-hot encoded vectors for training and testing.
6. Train the Model: The model is trained on the training data and validated on the validation set for 10 epochs. A batch size of 128 is used for training.
7. Evaluate the Model: Finally, the trained model is evaluated on the test set, and the test accuracy is printed.
   
**Opening the Code in Google Colab:**
1. To open and run the code in Google Colab, follow these steps:
2. Go to the GitHub repository containing the code.
3. Click on the .ipynb notebook file.
4. On the top-right corner of the notebook page, you'll see a "Open in Colab" button. Click on it to open the notebook in Google Colab.
5. Google Colab will open the notebook in a new tab. You can now run the code.
