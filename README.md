# ASL Sign Language Recognition

## Overview

This project leverages MediaPipe and Long Short-Term Memory (LSTM) networks to recognize American Sign Language (ASL) gestures. Initially designed to recognize five key signs, the system is built to expand into a larger vocabulary for comprehensive communication.

## Features

- **Real-Time Recognition**: Utilizes MediaPipe for efficient hand tracking and keypoint detection.
- **Fast Training**: Requires less data, allowing for quicker model training and improved performance due to the use of LSTM Neural Network.
- **Scalable**: Easily extend the vocabulary to include more signs and phrases, accommodating regional variations and dialects.

## Expansion Potential

Future development can incorporate:

- Additional signs and contextual phrases for enhanced communication.
- Integration of audio inputs and outputs for a multi-modal approach.

## Requirements

- Python 3.x
- OpenCV
- MediaPipe
- TensorFlow/Keras
- scikit-learn
- matplotlib
- numpy
- json
- os

## Installation

To install the necessary libraries, run:

```bash
pip install opencv-python mediapipe tensorflow scikit-learn matplotlib numpy
```

## Usage

Run the main script to start recognizing ASL signs through your webcam. The recognized gestures will be displayed in real-time.
