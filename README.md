# Sign Language Recognition using Deep Learning

Overview

This project presents a deep learning-based Sign Language Recognition system built using Convolutional Neural Networks (CNNs).
It can recognize American Sign Language (A–Y, excluding J and Z) from grayscale hand gesture images.

Motivation

Communication barriers between hearing-impaired individuals and others are still a global challenge.
This project aims to leverage Computer Vision and Deep Learning to bridge that gap by translating static sign gestures into readable letters, making technology more inclusive and accessible.


-Model:

Custom CNN trained on the Sign Language MNIST dataset (28×28 grayscale images, 24 classes).
Optimizer: Adam
Loss: Categorical Crossentropy
Regularization: Dropout (0.5)


-Results:

Metric	Score
Accuracy	94.28%
Macro F1-score	0.9389


-Dataset:

Dataset: Sign Language MNIST (Kaggle)
27,455 training images, 7,172 testing images
Image size: 28×28 pixels (grayscale)
24 classes (A–Y excluding J and Z)

-Future Work:

Extend to video-based word recognition (CNN+LSTM)
Add Grad-CAM explainability
Deploy on mobile using TensorFlow Lite
