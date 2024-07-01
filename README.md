# Waste-Identifier-and-Classifier
An AI-based Image Classification system, enabling precise identification of waste either as "Biodegradable" or "Recyclable". Increasing recycling rates and promoting composting of biodegradable waste, constituting to reducing landfill waste.

Trained 3 different deep learning models: CNN, VGG16 and ResNet50V2 for comparative analysis and achieved highest accuracy of 93 percent through VGG16 model.

## Table of Contents
- [Introduction](#introduction)
- [Requirements](#requirements)
- [Dataset](#dataset)
- [Files](#files)

## Introduction
The goal of this project is to identify and classify image data into predefined categories. This project demonstrates basic image preprocessing, , and classification using machine learning techniques.

## Requirements
- Python 3.x
- NumPy
- Pandas
- scikit-learn
- matplotlib
- keras
- tensorFlow
- glob
- seaborn
- sklearn

## Dataset
Combined different data available through the free distribution license, from Kaggle. Composed and pre-processed data to make it binary. The data consist of two classes “Recyclable” and “Biodegradable”. Both classes contain 13951 images each, making a total of 27902 images in the whole dataset. The images are divided in the ratio of 80:20 for training and testing respectively.

## Files
- `Classification_CNN.ipynb`: The main script to run the image classification with CNN model.
- `Classification_ResNet50V2.ipynb`: The main script to run the image classification with ResNet50V2 model.
- `Classification_VGG16.ipynb`: The main script to run the image classification with VGG16 model.
