# Real-Time Handwritten Digit Classification System ✍️🔢

An intelligent deep learning-based image classification system that recognizes handwritten digits in real time using a Convolutional Neural Network (CNN). The system processes user-drawn input, normalizes pixel values, and predicts digits (0–9) instantly with high accuracy to assist in digital handwriting recognition.

## Features
- ✍️ Interactive drawing canvas for live testing
- ⚡ Fast real-time inference using a trained CNN
- 🎯 High classification accuracy (>98%) on MNIST dataset
- 📊 Instant probability confidence score for predicted digits
- 🖼️ Automated image preprocessing and pixel normalization
- 🌐 Lightweight web application interface

## Tech Stack
- Python
- TensorFlow / Keras
- Gradio
- OpenCV
- NumPy
- Matplotlib

## How It Works
1. Captures user drawing from the interactive canvas.
2. Preprocesses the image (converts to grayscale, resizes to 28x28, and normalizes pixel values).
3. Passes the formatted image through the Convolutional Neural Network (CNN).
4. Predicts the digit (0–9) using a Softmax classification layer.
5. Displays the top predicted digit along with confidence scores in real time.

## Applications
- Form digitization and automated document processing
- Postal code and check number recognition
- Educational tool for machine learning & computer vision
- Interactive AI demo for digital handwriting recognition

## Future Enhancements
- Multi-digit handwritten sequence recognition
- Custom dataset upload and custom drawing import
- Data augmentation for varied handwriting styles
- Model conversion to ONNX / TensorFlow Lite for mobile edge deployment
- Real-time webcam digit detection

## Project Links & Live Demo
* **Live Interactive Web App (Gradio):** [Launch Live Gradio Interface](https://f5e9147a950de624f0.gradio.live)
* **Google Colab Notebook:** [View Colab Source & Training Code](https://drive.google.com/drive/folders/1oVQJwOaa-EauHOWHU_iJx19JJXU7o1X6?usp=drive_link)
