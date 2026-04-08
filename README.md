# AI 600 Deep Learning - Assignment 3

**Author:** Mubeen Ahmed  
**Roll No:** 25280101 (MS-AI)  
**Course:** AI 600 - Deep Learning, Spring 2026  
**Date:** April 8, 2026

## Assignment Overview

This repository contains the full solution to Assignment 3 for the AI 600 Deep Learning course. The project is divided into an analytical study of CNN mechanics and a series of programming experiments focusing on model design, shortcut learning, and interpretability.

### 1. Analytical Section
* **Toy-CNN Derivation**: Manual forward and backward pass calculations for a convolutional layer, including ReLU activation gradients.
* **Filter Gradient Analysis**: Identification of dominant filter weights based on input pixel intensity and upstream gradients.
* **Pooling & Normalization**: Mathematical analysis of Global Max Pooling, Layer Normalization, and the spatial properties of translation invariance.

### 2. Programming Section
* **Custom MNISTNet**: Design of a compact CNN with fewer than 50,000 parameters (final count: 29,882) achieving a test accuracy of 99.27%.
* **Shortcut Learning (Colored-MNIST)**: Investigation into how models prioritize simple color cues over complex shape features, resulting in an 8.55 percentage point accuracy drop on unbiased data.
* **Transfer Learning (STL-10)**: Fine-tuning a ResNet-18 model with a frozen ImageNet backbone to achieve 76.75% accuracy on a limited dataset.
* **Interpretability**: Implementation of GradCAM to visualize class-discriminative heatmaps and analyze failure modes like background confusion.

---

## Repository Structure

The complete code and project files can be accessed via this GitHub repository.

```text
.
├── assignment_3.ipynb          # Implementation of MNIST, C-MNIST, and STL-10 experiments
├── assignment_3_report.pdf     # Technical report containing derivations and analysis
├── README.md                   # This file
└── Output/                     # Generated results and visualizations
    ├── task1a_mnist_history.png   # Training curves for MNISTNet
