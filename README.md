# Deep Learning Based Survelliance System Using Face Recognition

A Python-based residential surveillance system leveraging deep learning for real-time face detection and recognition. This application enables secure and efficient identification by comparing live video frames against archived facial data.

Features
- Real-time face detection and recognition
- Image registration system for adding new users
- Optimized face-matching pipeline using archived data
- High accuracy and low-latency performance
- Deep learning-powered using Google’s FaceNet model

Requirements
- Python: 3.5 or higher
- Install required libraries via pip:
  pip install tensorflow==1.12.0 scikit-learn==0.19.1 scipy==0.17.0 Pillow==7.0.0 opencv-python==4.0.0.21 numpy==1.16.1

Notes
- Ensure your webcam is connected and accessible
- The model uses FaceNet for feature extraction
- The classifier is trained on the registered images using a pre-defined pipeline

Disclaimer

This is a research-level prototype and should not be deployed in production without additional security, error handling, and performance optimizations.
