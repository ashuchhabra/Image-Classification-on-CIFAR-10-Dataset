# Image-Classification-on-CIFAR-10-Dataset

## Data Source
https://www.cs.toronto.edu/~kriz/cifar.html

## About the Dataset
The CIFAR-10 dataset consists of 60000 32x32 RGB colour images with 10 classes, total of 6000 images per class. There are 50000 training images and 10000 test images.

The dataset is divided into five training batches and one test batch, each with 10000 images.

The test batch contains exactly 1000 randomly-selected images from each class.

The training batches contain the remaining images in random order, but some training batches may contain more images from one class than another. Between them, the training batches contain exactly 5000 images from each class.

These are the classes in the dataset:

airplane
automobile
bird
cat
deer
dog
frog
horse
ship
truck

## Results
1. When tried with a artificial neural network, got an accuracy of 55% on the training data. To improve the accuracy , CNN model is applied before the densely connected network.
2. After applying the CNN, both validation and test accuracy got improved to 86.43%.
