#  Sign Language Recognition using Deep Learning


 Overview

Developed a deep learning-based Sign Language Recognition system using Convolutional Neural Networks (CNNs).

Recognizes American Sign Language (A–Y, excluding J and Z) from grayscale hand gesture images.

Designed for accessibility and inclusivity, enabling seamless communication between hearing-impaired and non-hearing individuals.

 Motivation

Communication barriers for the hearing-impaired remain a global challenge.

This project leverages Computer Vision and Deep Learning to translate static sign gestures into readable letters.

The goal is to make technology more inclusive, accessible, and human-centered.

 Model

Architecture: Custom CNN

Dataset: Sign Language MNIST (28×28 grayscale images, 24 classes)

Optimizer: Adam

Loss Function: Categorical Crossentropy

Regularization: Dropout (0.5)

 Results
Metric	Score
Accuracy	94.28%
Macro F1-score	0.9389
 Dataset Details

Source: Sign Language MNIST – Kaggle

Training Samples: 27,455

Testing Samples: 7,172

Image Size: 28×28 (grayscale)

Classes: 24 (A–Y, excluding J and Z)

 Future Work

Extend to video-based word recognition using CNN + LSTM architectures.

Implement Grad-CAM for visual explainability.

Deploy on mobile devices using TensorFlow Lite for real-time offline recognition.
