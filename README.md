# Face Detection & Recognition

This is a Python-based face detection and recognition system using OpenCV and a K-Nearest Neighbors (KNN) classifier.

## Features

- Detects human faces in real-time from webcam or image input.
- Recognizes known faces using KNN classification.
- Stores face data and labels using Pickle.
- Lightweight and easy to use.

## Libraries Used

- `cv2` (OpenCV)
- `numpy`
- `os`
- `pickle`
- `csv`
- `sklearn.neighbors.KNeighborsClassifier`

## Folder Structure

project-root/
├── face_data/ # Folder to store face images and data
├── train.py # Script to train the KNN model
├── detect.py # Main script to detect and recognize faces
├── data.pickle # Pickled face embeddings and labels
└── README.md
