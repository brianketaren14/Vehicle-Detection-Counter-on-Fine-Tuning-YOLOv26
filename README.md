# Vehicle Detection and Counter with Fine-Tuned YOLOv26

This project focuses on vehicle detection and counting using a fine-tuned YOLOv26 model. The goal is to identify vehicles in images or video frames and count them automatically, which can be useful for traffic monitoring, smart surveillance, and computer vision applications.

## Project Overview

The system uses deep learning-based object detection to locate vehicles in a scene and track the number of detected objects. By fine-tuning a pretrained YOLOv26 model on a custom dataset, the model is adapted to perform better on specific vehicle detection tasks.

## Main Objectives

- Detect vehicles in images and video frames
- Count the number of vehicles present in each scene
- Improve detection performance through fine-tuning
- Provide a practical example of object detection and counting in real-world applications

## Features

- Vehicle detection using YOLOv26
- Automatic counting of detected vehicles
- Training pipeline with model evaluation
- Inference on images
- Visualization of detection results and training metrics

## Technologies Used

- Python
- PyTorch
- Ultralytics YOLO
- Jupyter Notebook
- OpenCV
- Matplotlib

## Project Structure

- `Vehicle Detection + Counter on Fine Tuning YOLOv26.ipynb` – main notebook containing data preparation, training, validation, and inference
- `runs/detect/train/` – training outputs, metrics, plots, and trained weights
- `runs/detect/val/` – validation results
- `runs/detect/predict/` – prediction outputs

## How It Works

1. A pretrained YOLOv26 model is loaded.
2. The model is fine-tuned on a vehicle dataset to improve detection accuracy.
3. The trained model is used to detect vehicles in input images or video frames.
4. Each detected vehicle is counted and visualized in the output.

## Training and Inference

The notebook contains the complete workflow for:

- preparing the dataset
- training the model
- validating the model
- saving the best weights
- running inference for detection and counting

## Results

The training process produces:

- detection performance metrics
- confusion matrix
- precision/recall-related visualizations
- trained model weights for deployment

## Usage

To run the project, open the notebook and execute the cells step by step. The trained model can then be used to detect and count vehicles from new images or video input.

## Why This Project Matters

Vehicle detection and counting are important in modern intelligent transportation systems. This project demonstrates how deep learning can be applied to automate traffic analysis and support decision-making in real-world environments.

## Acknowledgment

This project is built using the YOLO ecosystem and demonstrates the practical use of object detection for vehicle counting tasks.
