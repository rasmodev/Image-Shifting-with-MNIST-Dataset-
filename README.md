# Image-Shifting-with-MNIST-Dataset
This GitHub repository provides Python code and functions for shifting images within the MNIST dataset. The repository demonstrates how to load the dataset, visualize sample digits,
and perform image-shifting operations such as shifting up, down, right, and left. The code serves as a valuable resource for understanding and implementing image-shifting techniques
for data augmentation in machine learning projects. By leveraging these functions, users can easily shift images to increase the amount of training data and potentially enhance the
accuracy of their models.

# Image Shifting Functions
This repository contains a set of simple Python functions for shifting images in various directions. Shifting images can be useful for increasing the amount of data available for training and potentially improving the accuracy of machine learning models.

# Load Data
To begin, we will load the MNIST dataset from the scikit-learn (sklearn) library and examine one of the images in the dataset. The goal of this group work is to understand how to shift an image, so we won't need to split the dataset. We can focus on a few digits in the dataset for this task.

# Shifting Images
To shift images, we will utilize the shift function from the scipy.ndimage.interpolation module. The following sections describe different image shifting operations.

## 2.1 Shift Image Up
First, let's pick an image from the dataset and view it. Then, we can write a function to shift the image up by 1 pixel. You can test the function by shifting the image up by about 5 pixels and observe the change in the digit's position.

## 2.2 Shift Image Down
Similar to the previous section, we'll pick an image from the dataset and view it. Then, we'll write a function to shift the image down by 1 pixel. You can test the function by shifting the image down by about 5 pixels and observe the change in the digit's position.

## 2.3 Shift Image Right
Next, we'll pick an image from the dataset and view it. Then, we'll write a function to shift the image right by 1 pixel. You can test the function by shifting the image to the right by about 5 pixels and observe the change in the digit's position.

## 2.4 Shift Image Left
Lastly, we'll pick an image from the dataset and view it. Then, we'll write a function to shift the image left by 1 pixel. You can test the function by shifting the image to the left by about 5 pixels and observe the change in the digit's position.

Feel free to explore the provided functions and experiment with different pixel shift amounts to gain a better understanding of image shifting techniques.

Please note that this repository and the included functions are written in Python and require relevant dependencies to be installed for proper execution.
