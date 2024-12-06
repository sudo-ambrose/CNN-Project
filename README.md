
# Deep Learning: Image Classification with CNN

This project contains two image classifier that are able to differentiate between 6 different animals and 4 different vehicles such as birds, cats, deers,dogs, frogs, horses, ships and trucks.
---
---
## About
This project focuses on image classification using the CIFAR-10 dataset. It compares two approaches:

A custom CNN model built from scratch.
A transfer learning approach using a pretrained ResNet50V2 model fine-tuned on CIFAR-10.

The goal is to evaluate the performance of these two methods in terms of accuracy, loss, and class-wise metrics like precision, recall, and F1-score.

---
## Features
Custom CNN:

Multi-block convolutional layers with batch normalization.
Dropout layers for regularization.
Designed specifically for CIFAR-10 image resolution and class diversity.
ResNet50V2 Transfer Learning:

Pre-trained on ImageNet.
Fine-tuned on CIFAR-10 with frozen and unfrozen layers in separate phases.
Data augmentation for better generalization.

## Acknowledgments
TensorFlow for providing the frameworks used.
CIFAR-10 dataset creators.
The open-source community for helpful tutorials and resources.

## Getting Started
### Prerequisites
List any software or dependencies required to run the project.
```bash
Python 3.8+
TensorFlow 2.10+
NumPy  1.26.4+
Matplotlib 3.8.0+
scikit-learn 1.5.2+


