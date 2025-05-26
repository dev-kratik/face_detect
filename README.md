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

```project-root/
├── detector.py #Main script to detect and recognize faces 
├── feed_data.py # Script to train model
├── data  #Folder to store face images and data
     ├── faces_data.pkl
     ├── haarcascade_frontalface_default.xml
     ├── names.pkl
└── README.md
```

## Usage

1. **Collect face data**:
   Run feed_data.py to collect face images and save them in `data/` with proper labeling.

2. **RUN**:
   Run detect.py to detect faces which are trained to the model.



