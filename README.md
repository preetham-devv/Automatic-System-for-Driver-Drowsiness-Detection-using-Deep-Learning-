# Automatic-System-for-Driver-Drowsiness-Detection-using-Deep-Learning-
Driver Drowsiness Detection System

This project implements a deep learning-based driver drowsiness detection system using computer vision and transfer learning (Inception v3). The system monitors the driver’s eye state (open/closed) using a camera and alerts the driver if drowsiness is detected.

Features

Real-time drowsiness detection
Transfer learning using Inception v3
Eye detection with OpenCV and Haar Cascade
Achieves an accuracy of 87.4%
Dataset

The model uses the MRL Eye Dataset for training.

Installation

Clone the repository:
bash
Copy code
git clone https://github.com/username/Driver-Drowsiness-Detection.git
cd Driver-Drowsiness-Detection
Install dependencies:
bash
Copy code
pip install -r requirements.txt
Usage

Run the detection system:
bash
Copy code
python driver_drowsiness_detection.py
The system will use the camera to detect the driver’s eye state and trigger an alarm when drowsiness is detected.
Model Architecture

The project utilizes Inception v3 for feature extraction, and the facial features (eyes) are detected using OpenCV.

Results

Training Accuracy: 87.4%
Test Accuracy: 87.4%
Future Improvements

Incorporating a better night vision camera
Extending the model to detect additional facial features (e.g., yawning)
License

This project is licensed under the MIT License.

