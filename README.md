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

bash

git clone https://github.com/yourusername/emotion-detection.git
cd emotion-detection
Install dependencies:

bash
pip install -r requirements.txt
Download pre-trained model:

bash
wget https://example.com/model.h5 -O model/model.h5
Usage

Run the application:

streamlit run inference.py
Access the web interface at http://localhost:8501

Allow camera access when prompted
