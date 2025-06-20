# 🚗 Self-Driving Car using Deep Learning (Udacity Simulator)

<p align="center">
  <img src="https://user-images.githubusercontent.com/12345678/placeholder.gif" alt="Self-driving car demo" width="80%">
</p>

## 🧠 Project Overview

This project demonstrates an end-to-end deep learning approach for autonomous driving using the Udacity simulator. The system learns to predict steering angles from front-facing camera images using a convolutional neural network (CNN) based on NVIDIA's architecture.

---

## 📁 Project Structure

```bash
.
├── drive.py               # Real-time inference and communication with simulator
├── model.py               # Model definition using NVIDIA architecture
├── model.h5               # Trained model weights
├── data_preprocess.py     # Data balancing, augmentation and preprocessing
├── train.py               # Model training pipeline
├── track/                 # Dataset folder (cloned from GitHub)
│   ├── driving_log.csv
│   └── IMG/
└── README.md              # You're reading this :)
