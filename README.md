# USPS-Digit-Classification
Welcome to the USPS Digit Classification project! 🎉 This repository is dedicated to the binary classification of handwritten digits from the USPS dataset, focusing specifically on distinguishing between the digits '7' and '9'. Using a dataset with 16x16 grayscale images, this project aims to explore machine learning techniques for digit recognition.

Project Overview
Digit recognition is a fundamental task in machine learning, commonly used in various applications such as postal mail sorting, bank check processing, and digitized document management. This project simplifies the task by narrowing down the problem to a binary classification challenge: identifying whether a given image is a '7' or a '9'.

Dataset
The dataset used in this project is derived from the USPS digit dataset, provided in the file uspsall73.mat. It contains 16x16 grayscale images representing each of the 10 different handwritten digits. For the purposes of this project, only the images of '7's and '9's are utilized.

Key Points:
Image Resolution: 16x16 pixels
Classes: Handwritten digits '7' and '9'
Normalization: The data is z-score normalized to ensure each feature has a mean of 0 and a standard deviation of 1, which is crucial for many machine learning algorithms.
Goals
Data Preprocessing: Load and preprocess the data, focusing on the '7' and '9' digit classes.
Binary Classification: Train a binary classifier to distinguish between the two digit classes.
Evaluation: Evaluate the model's performance using appropriate metrics and visualize the results.
