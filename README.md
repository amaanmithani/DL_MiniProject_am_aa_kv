# Custom ResNet for CIFAR-10 Classification

This repository contains the implementation of a custom ResNet architecture optimized for the CIFAR-10 dataset, aimed at demonstrating advanced image classification techniques.
Kunaal Vadgama, Amaan Ansari, Amaan Mithani
New York University

## Project Overview

The project utilizes a modified ResNet architecture to classify images from the CIFAR-10 dataset, which includes 60,000 32x32 color images categorized into 10 classes. The model is tailored to provide high accuracy with efficient computational resource usage.

## Features

- **Custom ResNet Architecture**: Modified version of the ResNet architecture with optimizations for CIFAR-10.
- **Data Augmentation**: Incorporates random horizontal flipping and random cropping to improve model robustness.
- **Dynamic Learning Rate Adjustment**: Employs a OneCycleLR scheduler for optimal learning rate management.
- **Performance Visualization**: Includes scripts for plotting the confusion matrix, accuracy, and loss graphs over training epochs.

## Prerequisites

Before you begin, ensure you have met the following requirements:
- Python 3.8+
- PyTorch 1.7+
- torchvision
- matplotlib (for plotting)
- numpy

## Installation

Clone the repository to your local machine using:

```bash
git clone https://github.com/amaanmithani/DL_MiniProject_am_aa_kv.git
cd DL_MiniProject_am_aa_kv


