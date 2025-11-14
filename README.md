# LiDAR-Cross-Anomaly-Detection

LiDAR Anomaly Detection
This project demonstrates the use of Fuzzy C-Means (C-Means) clustering to build an anomaly detection system for LiDAR sensor data. The general approach is to train a model on a baseline of "normal" data (e.g., clear weather) to learn its core patterns.

Once trained, the model can be used to identify "anomalous" data (e.g., point clouds from adverse weather), which will have a different data signature and be flagged by the model.

This repository contains the methodology for this approach. All proprietary data and specific performance metrics have been omitted.
