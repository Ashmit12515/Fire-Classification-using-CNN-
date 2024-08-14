# Fire-Classification-using-CNN-
This repository contains a deep learning-based project focused on classifying images of fire using a Convolutional Neural Network (CNN). The model is trained to differentiate between images containing fire and those without it, which can be utilized for early fire detection in various applications, such as surveillance systems, environmental monitoring, and safety equipment.

# Project Overview
The objective of this project is to build a CNN model that can accurately classify images into two categories:
* Images with fire.
* Images without fire.
  
By leveraging the power of CNNs, the model can automatically learn to detect fire features from images, making it highly effective for real-world fire detection scenarios.

# Dataset
The dataset used for this project consists of images categorized into two classes:
* Fire: Images containing visible fire.
* No Fire: Images without any fire.
  
You can download the dataset from [https://drive.google.com/drive/folders/13TiYRBLEaB5MWdX1j3lm9atjWeT5JhL4?usp=sharing] or use any other dataset of your choice. The dataset should be organized into two folders: fire/ and no_fire/.

# Model Architecture
The model is built using the following CNN architecture:

* Input Layer: Accepts RGB images with a resolution of 224x224 pixels.
* Convolutional Layers: Multiple convolutional layers with ReLU activation and max-pooling for feature extraction.
* Fully Connected Layers: Dense layers for classification.
* Output Layer: A softmax layer for binary classification (Fire vs. No Fire).

You can find the model architecture details in the fire_classification_model.py file.
