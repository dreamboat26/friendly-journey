# Sports Analysis: Tennis and Football

## Overview

Welcome to the Sports Analysis repository, featuring two dynamic projects: Tennis Analysis and Football Analysis. These projects merge state-of-the-art techniques in machine learning and computer vision to delve deep into the realms of tennis and football, offering comprehensive insights into player performance, ball dynamics, and match statistics.

### Tennis Analysis

The Tennis Analysis project harnesses the power of machine learning to scrutinize tennis players in video footage. It employs advanced algorithms to measure player speed, ball shot velocity, and shot frequency. Utilizing YOLO for player and ball detection, complemented by Convolutional Neural Networks (CNNs) for court keypoints extraction, this project provides a hands-on opportunity to refine skills in machine learning and computer vision.

![screenshot](https://github.com/dreamboat26/friendly-journey/assets/125608791/cb15910f-222d-4d6f-9c93-ca70f0c86324)

### Football Analysis

The Football Analysis project is a multifaceted endeavor aimed at detecting and tracking players, referees, and footballs in videos. Leveraging YOLO, an elite AI object detection model, it implements sophisticated methodologies such as team assignment based on t-shirt colors using Kmeans, optical flow for camera movement assessment, and perspective transformation for spatial representation. This holistic approach facilitates precise measurement of player movement in meters and facilitates calculations of speed and distance covered, addressing real-world challenges in sports analysis.

![screenshot](https://github.com/dreamboat26/friendly-journey/assets/125608791/35e9442e-439a-4102-9189-6ad968c81780)

## Models Used

### Tennis Analysis
- YOLO v8 for player detection
- Fine-Tuned YOLO for tennis ball detection
- Court Keypoint Extraction

### Football Analysis
- YOLO for player, referee, and football detection

## Training

### Tennis Analysis
- Training of Tennis Ball Detector with YOLO: `training/tennis_ball_detector_training.ipynb`
- Training of Tennis Court Keypoints with PyTorch: `training/tennis_court_keypoints_training.ipynb`

### Football Analysis
- Trained YOLO v5 model: [Download Trained YOLO v5 (https://drive.google.com/file/d/1R0LtrjL5KFKe9dMUH3PsklMX2_eJ1E0S/view?usp=drive_link)]

## Requirements

To run these projects, ensure you have the following dependencies installed:

- Python 3.x
- ultralytics
- PyTorch
- OpenCV
- NumPy
- Matplotlib
- Pandas

Feel free to explore each project individually and contribute to their enhancement. Let's elevate sports analysis together!

