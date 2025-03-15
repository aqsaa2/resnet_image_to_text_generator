# Image Caption Generator

This project implements an image caption generator using a deep learning model. It takes an image as input and generates a textual description (caption) for it.

## Overview

The application is built using Flask, Keras, and TensorFlow. It utilizes a ResNet50 model for feature extraction and an LSTM-based model for generating captions. The process involves:

1.  **Image Upload:** Users upload an image through a web interface.
2.  **Feature Extraction:** The ResNet50 model extracts features from the uploaded image.
3.  **Caption Generation:** An LSTM model, trained on a dataset of images and captions, generates a textual description based on the extracted features.
4.  **Display Caption:** The generated caption is displayed to the user.
