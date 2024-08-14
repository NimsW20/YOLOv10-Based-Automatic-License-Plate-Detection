# YOLOv10 Object Detection Project

## Introduction

Welcome to the YOLOv10 Object Detection Project! This repository contains the implementation of an object detection system using YOLOv10, the latest iteration in the YOLO (You Only Look Once) family of models. I developed this project by referring to the paper “YOLOv10: Real-Time End-to-End Object Detection” by Ao Wang, Hui Chen, Lihao Liu, Kai Chen, Zijia Lin, Jungong Han and Guiguang Ding, the YOLOv10 documentation, and a tutorial by Nicolai Neilsen.

## What is YOLO?

YOLO (You Only Look Once) is a state-of-the-art, real-time object detection system. Unlike traditional object detection systems that repurpose classifiers or localizers to perform detection, YOLO frames object detection as a single regression problem, straight from image pixels to bounding box coordinates and class probabilities.

## Evolution of YOLO

YOLO models are built upon the Darknet framework, an open-source neural network framework written in C and CUDA. YOLO has undergone significant advancements through multiple versions. From its inception, YOLO has consistently pushed the boundaries of real-time object detection. Each iteration introduced innovative techniques and optimizations, leading to remarkable improvements in speed, accuracy, and efficiency.

## Features of YOLOv10

YOLOv10 brings several new features and improvements over previous versions:
- **NMS-free Training**: Eliminates the need for Non-Maximum Suppression during training, simplifying the process and improving efficiency.
- **Lightweight Classification Heads**: Utilizes lightweight heads for classification, enhancing speed without compromising accuracy.
- **Spatial-Channel Decoupled Downsampling**: Implements a novel downsampling technique that decouples spatial and channel information, leading to better feature extraction.
- **Rank-Guided Block Design**: Incorporates a rank-guided design for network blocks, optimizing the architecture for better performance.

**Libraries and Tools**

Uterlytics was used for data analysis and visualization.
Data Preparation: Dataset was downloaded from Roboflow and manually labelled to create accurate annotations.
