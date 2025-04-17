# Emotion-Detection-System
Overview

A real-time emotion detection system that analyzes facial expressions using deep learning and computer vision. The system classifies emotions (Happy 😊, Sad 😢, Angry 😠, etc.) from live webcam feed and provides an interactive visualization.

✨ Key Features
Real-time facial emotion detection (7 basic emotions)

468-point facial landmark tracking using MediaPipe

CNN-LSTM hybrid model for improved accuracy

Streamlit-based web interface

Privacy-focused (no data leaves your device)

Cross-platform support (Windows, macOS, Linux)

🛠️ Technologies Used
Technology	Purpose
Python 3.8+	Core programming language
OpenCV	Video processing and face detection
MediaPipe	Facial landmark detection
TensorFlow/Keras	Deep learning model
Streamlit	Web application interface
NumPy	Numerical computations
🚀 Getting Started
Prerequisites
Python 3.8+

Webcam

pip package manager

Installation
Clone the repository:



git clone https://github.com/HemantiRaj/Emotion-Detection-System
cd emotion-detection
Install dependencies:


pip install -r requirements.txt
Download pre-trained model:


Run the application:

streamlit run inference.py

Allow camera access when prompted
