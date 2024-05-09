# CV-case-study
 
Data used : cifar_10
Framework : tensderflow 2

Great! Here's the updated introduction for your GitHub repository README, focusing on exploring best practices in computer vision:

---

# Exploring Best Practices in Computer Vision with CNNs

Welcome to our repository dedicated to exploring best practices in computer vision using Convolutional Neural Networks (CNNs). Through a series of notebooks, we investigate various approaches, including building models from scratch, applying data augmentation, and leveraging transfer learning with different architectures such as ResNet50 and VGG16.

## Introduction

Computer vision plays a pivotal role in numerous applications, from image recognition to object detection and beyond. CNNs have emerged as the cornerstone of modern computer vision systems, offering remarkable performance in understanding and processing visual data.

## Project Objective

In this project, our primary objective is to examine the effectiveness of different techniques in improving the accuracy of CNN models. We aim to address the fundamental question: Is more always better? While complex architectures, extensive data augmentation, and transfer learning are often touted as key strategies for enhancing performance, our exploration seeks to challenge this assumption.

## Key Questions Explored

Through our notebooks, we seek to answer several key questions:

- Does building a CNN from scratch outperform transfer learning with pre-trained models like VGG16 or ResNet50?
- How does the application of data augmentation techniques impact model performance across different architectures?
- Is there a point where increasing model complexity leads to diminishing returns in accuracy?

models ranked by peformance (best to worst) : 
1- Resnet50 - no data augmentaion 
2- Resnet50 - with data augmentaion
3- CNN from scratch model with augemenation 
4- VGG16 - with data augmentaion

Project Structure

* CNN.ipynb: Jupyter Notebook file containing the implementation of a convolutional neural network (CNN) from scratch for image classification.
* RESNET_TRANSFER.ipynb: Jupyter Notebook file demonstrating transfer learning using a pre-trained ResNet model.
* RESNET_TRANSFER_AUG.ipynb: Jupyter Notebook file showcasing transfer learning with data augmentation techniques.
* VGG_TRANSFER.ipynb: Jupyter Notebook file illustrating transfer learning with a pre-trained VGG model.
* README.md: This file, providing an overview of the project and instructions for usage.
