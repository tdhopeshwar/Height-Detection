# Height Detection using Deep Learning
This repository contains the implementation of a Height Detection model using deep learning techniques. 
The project involves detecting a person's height in real time using a camera feed and models based on YOLO and MiDaS for depth and object detection.

## Project Overview
The primary goal of this project is to detect a person's height from real-time camera input. The approach involves using a combination of object detection and depth estimation to accurately predict height.

## Features
**Real-time Height Detection:** Utilizes a camera feed to estimate the height of a person.
**YOLO-based Object Detection:** Uses the YOLO (You Only Look Once) model for identifying the person in the camera feed.
**MiDaS Depth Estimation:** Leverages the MiDaS model to estimate the depth of objects in the scene.
**Height Prediction Model:** A custom height prediction model (height_prediction_model.h5) that refines the height estimate based on the person's position in the frame and other contextual information.

## Dataset
The Height Prediction Mode was tained on a dataset that includes images of people with known heights. The dataset contains labeled height data along with camera feed images. If you're working with the same dataset, ensure it's structured correctly in your project.

## Height Calculation
The Model uses the lowermost pixel of the person in frame to calculate height from the pixels

## Prerequisites
* Python 3.x
* Git
* TensorFlow/Keras
* OpenCV
* YOLOv5 or YOLOv8
* MiDaS for depth estimation
