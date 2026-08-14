# Landmark Detection

## Overview

This project demonstrates landmark detection using two different approaches:

1. Facial Landmark Detection using MediaPipe Face Mesh
2. Custom Landmark Detection using PyTorch and CNN

## 1. Facial Landmark Detection

MediaPipe Face Mesh is used to detect facial landmarks such as the eyes, nose, mouth, and jawline from an image.

The model can detect 468+ facial keypoints and is suitable for real-time computer vision applications.

## 2. Custom Landmark Detection

A Convolutional Neural Network (CNN) is designed and trained using PyTorch to detect landmark points on synthetic geometric shapes.

The model predicts the coordinates of three corner points of a triangle.

## Technologies Used

- Python
- OpenCV
- MediaPipe
- NumPy
- Matplotlib
- PyTorch
- Torchvision

## Applications

- Facial expression analysis
- Face-related computer vision
- Augmented Reality (AR)
- Pose and keypoint detection
- Object tracking
- Industrial inspection

## Project File

- `landmark_detection.ipynb` – Complete implementation of facial and custom landmark detection.

## How to Run

1. Open `landmark_detection.ipynb` in Google Colab or Jupyter Notebook.
2. Install the required Python libraries.
3. Run the notebook cells sequentially.

## Author

Praisy Priya
