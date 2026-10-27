# Indian Traffic Sign Recognition

Real-time Indian traffic sign recognition using OpenCV color-based detection and a CNN built with TensorFlow/Keras.

## Features
- HSV-based red sign detection
- Automatic ROI extraction from XML annotations
- CNN with data augmentation and early stopping
- Live webcam inference (confidence > 80%)

## Dataset
Indian Traffic Sign Image Dataset: add the Kaggle/source link here.

## Installation
pip install opencv-python numpy tensorflow scikit-learn

## Usage
1. Download the dataset and place it in the project folder.
2. Run the notebook cells in order.
3. Run the last cell for live webcam recognition (press `q` to quit).

## Tech Stack
Python, OpenCV, NumPy, TensorFlow/Keras, scikit-learn
