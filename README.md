# Sign Language Image Classification (CNN)

Convolutional Neural Network (CNN) for classifying 28×28 grayscale images of hand signs into letter classes.

## Overview
This project implements a CNN-based image classification pipeline for recognizing sign language characters from grayscale images.

- Task: Multiclass image classification  
- Input: 28×28 grayscale images  
- Output: Letter class  
- Model: Convolutional Neural Network (CNN)

## Technical Highlights
- Data preprocessing: normalization, reshaping, and one-hot encoding  
- Train/validation split  
- CNN architecture with convolution, pooling, and dropout layers  
- Categorical cross-entropy loss with softmax output  
- Prediction pipeline for unseen test data  

## Tech Stack
- Python  
- TensorFlow / Keras  
- NumPy  
- scikit-learn  

## Data
Dataset files (`train.csv`, `test.csv`) are not tracked in this repository due to size constraints.

## Attribution
This project was developed as part of the course *COMS 4701: Artificial Intelligence*  
at Columbia University. The overall project structure and some boilerplate code were
provided by the course staff. The CNN architecture, data preprocessing pipeline,
training logic, and prediction workflow were implemented by me.
