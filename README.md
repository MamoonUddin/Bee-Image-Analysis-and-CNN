# Bee Species and Health Classification with CNNs

This project focuses on using Convolutional Neural Networks (CNNs) to classify bee species and assess bee health based on images of bees. The dataset includes images of different bee species and their health conditions, aiming to build models that can accurately identify these attributes.

## Data Sources

The image dataset used for this project comes from the following Kaggle datasets:

- [Nave Bees Image Loading and Processing Dataset](https://www.kaggle.com/datasets/kamganganthony/nave-bees-image-loading-and-processin)
- [Honey Bee Annotated Images Dataset](https://www.kaggle.com/datasets/jenny18/honey-bee-annotated-images)

## Project Overview

This repository contains the code for the following main steps:

1. Data preprocessing and balancing
2. Subspecies classification CNN
3. Health classification CNN
4. Visualizing convolutional kernels

## Key Code Sections

### Data Preprocessing and Balancing

The dataset is preprocessed by resizing images to a consistent size and splitting it into training, validation, and test sets. Class imbalance is addressed using a balancing technique to ensure each class has a representative number of samples for training.

### Subspecies Classification CNN

A CNN model is developed to classify bee subspecies. The model architecture includes convolutional layers, max-pooling layers, and fully connected layers. Data is prepared with one-hot encoding for target labels, and data augmentation is applied for model generalization.

### Health Classification CNN

Another CNN model is designed to classify bee health conditions. Similar to the subspecies classification, the model architecture is defined with convolutional and fully connected layers. Data preprocessing and augmentation techniques are applied.

### Visualizing Convolutional Kernels

Convolutional kernels of both CNN models are visualized to understand how they capture features from input images. This helps in understanding the learned features and their contribution to accurate classifications.

## Project Summary

For a detailed summary of the project, please refer to the [Summary Section](#bee-species-and-health-classification-with-cnns-summary).

## Usage

To reproduce the results and insights from this project, you can follow the code provided in the [`main.ipynb`](main.ipynb) notebook.

## Conclusion

In this project, we successfully implemented CNN models for bee subspecies and health classification tasks. The models demonstrated promising accuracy in identifying bee attributes. Visualizing the convolutional kernels provided insights into the learned features and enhanced our understanding of the classification process.
