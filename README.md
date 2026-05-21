
# Hybrid Deep Learning-Based IDS for Network Anomaly Detection

A hybrid Intrusion Detection System (IDS) that combines Autoencoders, Unsupervised Clustering, and Deep Neural Networks (DNNs) to detect network anomalies and zero-day attacks using the NSL-KDD dataset.

## Overview

Traditional IDS models rely heavily on labeled datasets and struggle with unknown attacks. This project introduces a self-learning deep learning framework capable of identifying both known and novel threats without extensive labeled data.

### Features
Autoencoder-based feature extraction
Unsupervised anomaly clustering
Deep Neural Network classification
Binary and multi-class attack detection
Zero-day attack detection capability
Reduced dependency on labeled datasets
Dataset

The model uses the **NSL-KDD dataset** for training and evaluation.

**Classification Types**
**Binary**: Normal, Attack
**Multi-Class**: Normal, DOS, PROBE, R2L, U2R

**Tech Stack**
Python, TensorFlow / Keras, Scikit-learn, Pandas & NumPy

Architecture

<img width="1042" height="247" alt="image" src="https://github.com/user-attachments/assets/0d11e518-600b-4791-882e-815eb95684b7" />

**Goal**

To build a cost-effective and adaptive IDS capable of detecting evolving cyber threats and zero-day attacks with high predictive accuracy.

**Keywords**

Anomaly Detection Deep Learning IDS DNN Autoencoders Clustering Cybersecurity
