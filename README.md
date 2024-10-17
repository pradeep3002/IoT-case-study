# IoT-case-study
**Edge-Based Smart Surveillance: Real-Time Human Detection &amp; Tracking with Lightweight Models**

# Smart Surveillance Video Stream Processing at the Edge

## Real-Time Human Objects Tracking

This repository contains the case study and implementation details for a smart surveillance system that processes video streams at the edge for real-time human object tracking. This project is part of the Cloud-Based IoT (CSEN4011) course at the Department of Computer Science and Engineering, Gandhi Institute of Technology and Management.

### Authors
- Y. PRADEEP REDDY (BU21CSEN0600051)
- K. VINAY (BU21CSEN0600070)
- P. VENKATA DEEPAK (BU21CSEN0600117)

## Table of Contents
1. [Introduction](#introduction)
2. [Human Object Detection](#human-object-detection)
3. [Object Tracking](#object-tracking)
4. [Lightweight Human Tracking](#lightweight-human-tracking)
5. [Conclusion](#conclusion)

## Introduction
This project explores the implementation of smart surveillance in the context of smart cities, focusing on real-time object detection and tracking. It addresses challenges such as:
- Processing video streams from distributed data sources
- Reducing network load and latency
- Enhancing data security and privacy

## Human Object Detection
We implement two main algorithms for human object detection:
1. HOG+SVM (Histogram of Oriented Gradients + Support Vector Machine)
2. KCF (Kernelized Correlation Filters)

## Object Tracking
Our system uses a multi-tracker object queue to manage multiple objects across video frames. Key features include:
- Initialization of new trackers for detected objects
- Continuous tracking using KCF algorithm
- Handling of objects entering and leaving the frame

## Lightweight Human Tracking
We combine HOG+SVM for detection and KCF for tracking to achieve efficient and lightweight human detection and tracking, suitable for edge devices and resource-constrained environments.

## Conclusion
This project demonstrates the potential of edge-based video processing for smart surveillance, offering:
- Real-time monitoring capabilities
- Improved security and privacy
- Efficient operation in resource-constrained environments

For more details, please refer to the full case study document in this repository.

---

© 2024 Y. PRADEEP REDDY, K. VINAY, P. VENKATA DEEPAK. All Rights Reserved.
