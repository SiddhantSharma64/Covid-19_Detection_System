# COVID-19 Detection Using CNN

## Overview

This web application utilizes deep learning and computer vision to classify chest X-ray images as COVID-19, pneumonia, or normal. It provides real-time analysis to assist in the early detection and management of COVID-19 cases, leveraging a Convolutional Neural Network (CNN).

## Features

- Upload chest X-ray images from the file system or capture images using the camera.
- Classify images into three categories: COVID-19, pneumonia, or normal.
- Real-time predictions with confidence scores.
- User-friendly interface built with Flask.

## Technologies

- **Backend**: Flask, TensorFlow, Keras
- **Computer Vision**: OpenCV
- **Frontend**: HTML, CSS
- **Model**: Custom-trained CNN model

## Usage

1. Open the application at `http://127.0.0.1:5000`.
2. Upload a chest X-ray image from your device or capture an image using the camera.
3. Click "Upload" to see the prediction (COVID-19, pneumonia, or normal) and the associated confidence score.

## Dataset

Utilized the publicly available datasets for training, such as:

- [COVID-19 Radiography Database](https://www.kaggle.com/datasets/tawsifurrahman/covid19-radiography-database)  