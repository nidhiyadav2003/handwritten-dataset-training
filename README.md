## Project Description

This Python and Deep Learning project demonstrates the creation and training of an Artificial Neural Network (ANN) using the Keras library. The primary goal of the project is to achieve high accuracy on the CIFAR-10 dataset. The project utilizes various deep-learning libraries and techniques to accomplish this task.

### Libraries Used

The project makes use of the following libraries:

- Theano
- Keras
- TensorFlow
- PyTorch

### Dataset

The CIFAR-10 dataset is employed for this project. It is loaded using Keras and divided into training and testing sets. The dataset contains labeled images across ten classes, and it serves as the foundation for training and evaluating the ANN model.

### Implementation

The project involves the following key steps:

1. Loading the CIFAR-10 dataset using Keras.
2. Preprocessing the data: Reshaping the images into a flat format to prepare them for input to the ANN.
3. Creating the ANN model: A Sequential model is built using Keras, consisting of two hidden layers with sigmoid activation functions.
4. Compiling the model: The model is compiled with the Adam optimizer and sparse categorical cross-entropy loss function.
5. Training the model: The model is trained on the training data for a set number of epochs.
6. Making predictions: The trained model is used to predict classes for the testing dataset.
7. Evaluating the model: The accuracy of the model is evaluated on the testing data.

The implementation showcases the utilization of deep learning techniques to achieve accurate classification of CIFAR-10 images.

## README

### CIFAR-10 Deep Learning Project

This repository contains code and documentation for a Deep Learning project aimed at achieving high accuracy on the CIFAR-10 dataset using an Artificial Neural Network (ANN). The project utilizes Python and various deep-learning libraries such as Keras and TensorFlow. The goal is to showcase the implementation of a neural network for multi-class image classification.

### Project Structure

- `main.ipynb`: Jupyter Notebook containing the project code, including data loading, preprocessing, model creation, training, and evaluation.
- `README.md`: This file, provides an overview of the project, its purpose, and instructions for running the code.
- `data/`: This directory can be used to store the CIFAR-10 dataset. However, since the dataset can be loaded directly through Keras, it is not included in this repository.
  
### How to Use

1. Clone the repository to your local machine.
2. Install the required libraries, if not already installed, using `pip install tensorflow keras matplotlib seaborn`.
3. Open the `main.ipynb` notebook using Jupyter Notebook or Google Colab.
4. Run each cell in the notebook sequentially to execute the project code.
5. Observe the training progress and the evaluation accuracy achieved by the ANN model.
6. Customize and experiment with the code to further explore deep learning techniques.

Feel free to fork this repository, make improvements, or adapt it to other datasets and classification tasks.

**Note:** If you intend to run the code in `main.ipynb`, make sure you have the required libraries and dependencies installed.

### About the Author

This project was developed by NIDHI. Connect with me on [LinkedIn]([https://www.linkedin.com/in/your-profile/](https://www.linkedin.com/in/nidhi-y-0007a5221/)) to discuss more about deep learning, AI, and technology!

---
