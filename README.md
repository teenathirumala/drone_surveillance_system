# drone_surveillance_system
# Drone Surveillance and Detection System

This project implements an AI-powered drone surveillance system using computer vision techniques like object detection and tracking. The model is based on **YOLOv8** and includes preprocessing, fine-tuning, and multi-object tracking capabilities.

## 📁 Project Structure

- `yolopreprocessing.ipynb` – Preprocessing pipeline for training data (resizing, annotation formatting, etc.).
- `yolov8finetuning.ipynb` – Fine-tuning the YOLOv8 model on custom drone surveillance datasets.
- `trackingandredetction.ipynb` – Object tracking and re-detection logic post inference.
- `test_video.ipynb` – Testing pipeline for input videos or real-time feed.
- `drone_data.yaml` – Dataset configuration file compatible with YOLOv8.
- `.gitignore`, `.qodo/`, and other utility files.

## 🚀 Features

- Custom YOLOv8 fine-tuning for aerial imagery.
- Live object tracking and re-identification.
- Works with video files or real-time camera input.
- Modular notebooks for preprocessing, training, and evaluation.

## 🛠️ Requirements

- Python 3.8+
- PyTorch
- Ultralytics YOLOv8
- OpenCV
- NumPy
- Jupyter

Install dependencies:
```bash
pip install -r requirements.txt
