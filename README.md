# emotion-detection
A deep learning project to detect facial emotions from images using CNN. It uses a pre-trained mini_XCEPTION model trained on the FER-2013 dataset. Supports 7 emotions: Angry, Disgust, Fear, Happy, Sad, Surprise, Neutral. Built with TensorFlow, Keras, and OpenCV 
# Emotion Detection using Deep Learning

This project detects human facial emotions (e.g., Happy, Sad, Angry, etc.) from images using a convolutional neural network (CNN) trained on the FER-2013 dataset.

## Features
- Predicts 7 emotions from grayscale face images
- Uses a pre-trained Mini-XCEPTION model
- Can be run in Google Colab or locally (Jupyter Notebook)

## How to Use
1. Upload an image of a face
2. Load the pre-trained model
3. Run the prediction script to get the emotion label

## Dataset & Model
- Dataset: [FER-2013](https://www.kaggle.com/datasets/msambare/fer2013)
- Pretrained Model: `fer2013_mini_XCEPTION.119-0.65.hdf5` (used in Colab)
