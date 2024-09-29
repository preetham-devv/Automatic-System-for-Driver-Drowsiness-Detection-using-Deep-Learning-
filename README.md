# Driver Drowsiness Detection System

This repository contains the implementation of a driver drowsiness detection system using deep learning. The model leverages **Inception v3** and **OpenCV** for real-time eye state detection (open or closed) and alerts the driver if drowsiness is detected.

## Features
- Real-time monitoring of the driver’s eye state.
- Transfer learning with Inception v3 for high accuracy.
- Detection of drowsiness using OpenCV’s Haar Cascade for facial features.
- Achieves 87.4% accuracy on the test data.

## Abstract
The drowsiness of drivers and careless driving are significant reasons for road accidents, which result in the loss of valuable lives. This system proposes using transfer learning with **Inception v3** and **OpenCV** to build an efficient driver drowsiness detection system. The system utilizes the **MRL Eye Dataset** to detect eye closure, indicating drowsiness, and alerts the driver.

## Project Structure
- `/data/`: Contains the MRL Eye dataset (or link to the dataset if it's too large).
- `/models/`: Trained models and checkpoints.
- `/scripts/`: Python scripts for training and inference.
- `/output/`: Logs and results.

## Setup Instructions

### Prerequisites
- Python 3.x
- TensorFlow
- OpenCV
- Numpy
- Matplotlib

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/username/Driver-Drowsiness-Detection.git
   cd Driver-Drowsiness-Detection
