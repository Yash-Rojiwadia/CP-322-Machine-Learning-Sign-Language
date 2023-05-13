# Optical Character Recognition using Machine Learning

### Group Members

- Yash Rojiwadia - 203039360
- Obi Ihejirika - 190970850
- Anshul Khatri - 193313680

## Objective
The objective of this project is to develop an Optical Character Recognition (OCR) system capable of recognizing handwritten characters in images. The ability to convert real-world text and handwriting into digital text has numerous applications, such as automated document processing and text recognition in images. However, recognizing text in images is a challenging task due to variations in fonts, sizes, colors, and distortions.

## Dataset
For this project, we used the MNIST ("Modified National Institute of Standards and Technology") dataset, which is a popular dataset for training and testing machine learning algorithms designed to recognize handwritten digits. The dataset consists of a collection of 70,000 images of handwritten digits (0-9), with each image being 28x28 pixels. Each image has a corresponding label indicating the correct digit represented in the image.

## Approach
We utilized machine learning algorithms and image pre-processing techniques to train our OCR model on the MNIST dataset. Our approach involved:

1. Data pre-processing: We converted the images to grayscale, normalized the pixel values, and applied image enhancement techniques to improve the image quality.

2. Model training: We used a convolutional neural network (CNN) architecture to train our OCR model. We implemented the CNN using the Keras API with TensorFlow as the backend. We trained the model for 6679 epochs.

3. Model evaluation: We evaluated the model's performance on a test set of 10,000 images, which was not used during training. We measured the prediction accuracy of the model, which was found to be 94.26%.

## Results
Our OCR model achieved a prediction accuracy of 94.26% on the MNIST test set, which is a promising result for recognizing handwritten digits. We believe that with further optimization and fine-tuning of the model, we can improve the accuracy and extend our OCR system to recognize other characters and handwriting styles.
