# Deepfake Image Detection using Deep Learning (CNN + LSTM)
This project is aimed at detecting deepfake images using deep learning techniques. Deepfakes are AI-generated media that look real but are fake, and can be used maliciously in fake news, identity fraud, and cybercrimes. Our solution uses a combination of *Convolutional Neural Networks (CNN)* for spatial feature extraction and *Long Short-Term Memory (LSTM)* networks to learn sequential dependencies (for video frame support).

## Problem Statement
With the rise of deepfake content, detecting fake images and videos has become a major challenge. Manual detection is not reliable or scalable. This project attempts to automate the detection of such media using a trained deep learning model.

## Features
- Detects real vs fake images
- Uses CNN for feature extraction
- LSTM (optional) for sequence modeling in video frames
- Trained on real deepfake datasets
- High accuracy and precision
- Can be integrated with a simple UI using Streamlit

## Tech Stack
- Python
- TensorFlow / Keras
- OpenCV
- NumPy, Pandas
- (Optional) Streamlit for UI

## Dataset
We used publicly available datasets for deepfake detection:
- [FaceForensics++](https://github.com/ondyari/FaceForensics)
- [Deepfake Detection Challenge Dataset (DFDC)](https://ai.facebook.com/datasets/dfdc/)
