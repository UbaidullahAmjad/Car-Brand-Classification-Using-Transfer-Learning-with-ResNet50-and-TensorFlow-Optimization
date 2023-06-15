# Car-Brand-Classification-Using-Transfer-Learning-with-ResNet50-and-TensorFlow-Optimization

This repository contains code for performing Car Brand Classification using the ResNet50 model with TensorFlow and Keras.

## Overview

The code demonstrates how to fine-tune the ResNet50 model, a pre-trained deep learning model, on a custom dataset for image classification tasks. It covers the following steps:

1. Importing the necessary libraries
2. Defining constants for image size, batch size, and number of epochs
3. Enabling mixed precision for faster training
4. Specifying data paths for training and validation datasets
5. Determining the number of output classes
6. Applying data augmentation techniques to the training data
7. Loading the ResNet50 base model and freezing its weights
8. Creating the model architecture by adding custom layers
9. Compiling the model with an optimizer, loss function, and metrics
10. Loading the training and validation datasets
11. Training the model with early stopping and model checkpoint callbacks
12. Plotting the training and validation curves

## How to Use

To use this code, follow these steps:

1. Install the required libraries listed in the `requirements.txt` file.
2. Prepare your custom dataset by organizing images into class-specific directories.
3. Update the `train_dir` and `val_dir` variables in the code with the paths to your training and validation datasets.
4. Adjust the constants (`IMG_SIZE`, `BATCH_SIZE`, `EPOCHS`) based on your specific requirements.
5. Run the code and monitor the training progress and performance through the displayed logs and plotted curves.
6. Retrieve the best model weights saved by the model checkpoint callback for inference or further evaluation.

## Dependencies

The code is written in Python and relies on the following libraries:

- TensorFlow
- Keras

You can install the required dependencies using the following command:

```shell
pip install -r requirements.txt
