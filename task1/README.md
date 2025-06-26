This notebook documents my own experiment on the use of convolutional neural networks (CNNs) for emotion detection. 
Each model was constructed from the ground up, without the use of pre-trained architectures, in order to improve my comprehension of activation behavior and feature learning.
Important observations: In order to enhance generalization, I used sophisticated data augmentation and iteratively adjusted the CNN architecture. 
To visually evaluate the model's attention and confirm that it is focused on the appropriate face regions, I used Grad-CAM.
Dataset : https://www.kaggle.com/datasets/msambare/fer2013

Emotion Detection with Grad-CAM Visualization 
This project demonstrates an emotion detection system using a Convolutional Neural Network (CNN) trained on grayscale facial images. It also incorporates Grad-CAM (Gradient-weighted Class Activation Mapping) to visualize the decision-making process of the model.

 Features
- Emotion recognition on 48x48 grayscale images
- Pre-trained CNN model loaded from JSON and weights
- Grad-CAM heatmap visualization to interpret CNN focus
- Side-by-side image and heatmap display using Matplotlib

Emotions Detected
- Angry
- Disgust
- Fear
- Happy
- Sad
- Surprise
- Neutral

Dependencies
- Python 3.7+
- TensorFlow 2.x
- Keras
- NumPy
- OpenCV
- Matplotlib

