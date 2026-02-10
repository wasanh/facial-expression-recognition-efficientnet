# Facial Expression Recognition Using Attention-Enhanced EfficientNet

This repository contains the implementation and experimental results of a facial expression recognition (FER) system developed as part of a Pattern Recognition course project.

## Overview
The project proposes an EfficientNet-based convolutional neural network enhanced with Squeeze-and-Excitation (SE) attention mechanisms to improve discriminative feature learning. To address class imbalance in a custom-collected facial expression dataset, weighted sampling and Focal Loss are employed during training.

## Repository Structure
- `code/`: Implementation of the proposed FER model and training pipeline
- `paper/`: Final project paper in PDF format

## Dataset
The dataset used in this project is a custom-collected facial expression dataset. Due to privacy and ethical considerations, the dataset is not publicly released.

## Results
The proposed approach achieves stable convergence and balanced class-wise performance, as demonstrated by Macro-F1 scores and confusion matrix analysis.

## Requirements
- Python 3.x
- PyTorch
- torchvision
- numpy
- matplotlib
- scikit-learn

## Acknowledgments
This project was developed for academic purposes as part of a university Pattern Recognition course.
