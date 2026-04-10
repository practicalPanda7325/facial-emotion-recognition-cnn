# Facial Emotion Recognition using CNN

## Overview
This project focuses on facial emotion recognition using deep learning and hybrid approaches. 
The goal is to classify facial expressions into emotion categories using convolutional neural networks.

## Dataset
- FER2013 dataset
- Preprocessing steps:
  - Face detection and alignment
  - Normalization and resizing
  - Data augmentation

## Methodology
- CNN-based feature extraction for emotion classification
- Implementation of custom CNN architectures
- Comparison with hybrid approaches using classical classifiers such as:
  - Support Vector Machines (SVM)
  - Random Forest

## Experiments
- Evaluation of different CNN architectures
- Analysis of performance with and without hybrid classifiers
- Study of dataset imbalance handling using class-weighted loss

## Code
- `fer.ipynb`: Complete pipeline including preprocessing, training, and evaluation

## Setup

```bash
pip install -r requirements.txt
