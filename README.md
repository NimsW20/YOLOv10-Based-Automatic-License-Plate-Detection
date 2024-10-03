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

# Architecture
![Architecture](https://github.com/NimsW20/YOLOv10-Based-Automatic-License-Plate-Detection/blob/cae912a9bccccb7127786662e014ec52d3b855f6/images/image.png)

# Why version 10 is better?
YOLOv10 builds on the strengths of its predecessors with key enhancements in speed, accuracy, and efficiency. It introduces a more advanced backbone architecture and integrates attention mechanisms to improve detection in challenging environments, particularly for small or densely packed objects. With multi-scale prediction improvements and a streamlined detection head, YOLOv10 delivers higher accuracy (mAP) without compromising on real-time performance. Its optimized design for edge devices makes it lightweight, faster, and suitable for deployment in low-power environments, offering a superior balance of precision and speed compared to earlier YOLO versions.
![Yolo Versions Comparison](https://github.com/NimsW20/YOLOv10-Based-Automatic-License-Plate-Detection/blob/b568e17fb9e7f8243b536e42d02253d37720b9e6/images/Yolo%20versions%20comparison.png)

**Libraries and Tools**

Uterlytics was used for data analysis and visualization.
Data Preparation: Dataset was downloaded from Roboflow and manually labelled to create accurate annotations.

Note: This model can be used for realtime object detection as well. And we can use it for any custom dataset.
