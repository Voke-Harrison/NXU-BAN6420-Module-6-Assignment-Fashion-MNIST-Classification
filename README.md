# NXU-BAN6420-Module-6-Assignment-Fashion-MNIST-Classification
CONVOLUTIONAL NEURAL NETWORKS (PREDICTIVE ANALYTICS)
Image Classification Using Fashion MNIST Dataset and Keras.
BAN6420 Module 6 Assignment
Voke Harrison Edafejimue
Learner ID - 143304

The attached zip folder named 'Module 6 - Use of R and Python in Emerging Technologies' contains a Jupyter notebook call 'FashionMNISTClassification'. In this note book I used Predictive Analytics - Convolutional Neural Networks to carry out Image classifiction with a dataset called, Fashion Mnist.
The script carries out the following operations;
* Import the required libraries, data, model, optimizer and classes.
* The data is then split into training and testing data.
* The dimensions of the dataset is then displayed.
	* The Fashion MNIST dataset contains 60,000 training examples, 10,000 testing examples, 10 classes of fashion items images and all the images are 28x28 grayscale images.
* Next, a sample data is displayed using matplotlib's subplot().
* The data is then reshaped by converting the images to 3-channel images and adding an empty colour dimension to the dataset.
* Define the model architecture with 6 layers. Conv2D, MaxPooling2D, Conv2D, MaxPooling2D, Flatten and Dense.
* Compile and Build the model, used Adam optimizer to achiever learning rates with minimum loss, with a summary of the model displayed. This generated Total Parameters of 269,322 and 0 Non-trainable parameters.
* Now I trained the model with 5 epochs.This step gave a Training Accuracy of 90%, Training loss of 26%, Validation accuracy of 88% and validation loss of 34%.
* A model Analysis showing Training Accuracy vs Validation Accuracy and Training vs Validation loss with interpretation.
* Prediction was done for 16 items, that is a 4 x 4 grid  with interpretation.
