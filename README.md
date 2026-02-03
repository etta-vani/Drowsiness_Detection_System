# Driver Drowsiness Detection System

## Project Description
This project implements a real-time Driver Drowsiness Detection System using
computer vision techniques. The system monitors the driver's eye movements
using Haar Cascade classifiers and alerts the driver when drowsiness is detected.

## Technologies Used
- Python
- OpenCV
- Haar Cascade Classifier
- NumPy
- Computer Vision

## Features
- Real-time face and eye detection
- Drowsiness detection based on eye closure duration
- Audio/visual alert system
- Live camera monitoring

## Implementation
The project uses Haar Cascade classifiers for detecting facial features.
Eye closure is tracked over consecutive frames to identify drowsiness.
Threshold-based logic is used to trigger alerts.

## Customization
Implemented and customized by **Vani**:
- Added real-time name overlay on detection window
- Tuned eye-closure threshold for improved accuracy

## How to Run
1. Install dependencies
2. Run the main Python file
3. Allow camera access
4. Observe real-time detection
