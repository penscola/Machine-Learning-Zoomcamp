# Bee or Wasp Prediction Project

## Overview

This project aims to develop a machine learning model for predicting whether an image contains a bee or a wasp. Leveraging computer vision techniques, the model is trained on a dataset sourced from Kaggle to accurately classify these insect species.

## Model Architecture

The model is a Convolutional Neural Network (CNN) with the following layers:

- Input Layer: Conv2D (32 filters, 3x3 kernel, ReLU activation)
- MaxPooling2D Layer (2x2)
- Flatten Layer
- Dense Layer (64 neurons, ReLU activation)
- Output Layer (1 neuron, Sigmoid activation)

## Training and Results

The model is trained for 10 epochs using an image data generator with data augmentation. The key results include a median accuracy of approximately 77.25% and a standard deviation of the loss around 0.0967.

## Data Augmentation

Data augmentation techniques, such as rotation, shifting, and flipping, are applied to the training dataset to enhance model generalization.

## Saving Model Weights

The trained model weights are saved in the following file:

- './model/model_v1.h5'

## Getting Started

### Prerequisites

- Google Colab
- Python 3
- TensorFlow
- Matplotlib

### Installation

Clone the repository:

```bash
git https://github.com/penscola/Machine-Learning-Zoomcamp/tree/master/Deep_Learning
cd Deep_Learning
```

Install dependencies:

```bash
pip install -r requirements.txt
```

