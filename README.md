# Icebergs
Identify ships and icebergs from satellite images.

## Description
This is my submission to the Statoil Iceberg Classifier challenge on Kaggle: https://www.kaggle.com/c/statoil-iceberg-classifier-challenge. The challenge consists of creating a classifier that can distinguish ships from icebergs in a collection of satellite imagery data.

My approach was to denoise and perform data augmentation on the input images, train a convolutional neural network, then tune the classifier using TensorBoard.

This work was my capstone project for the Udacity Machine Learning Engineer Nanodegree program. The goal was to get a score better than the median score of the public leaderboard, which was 0.19387 at the time. My final score was 0.19186 (this is a log loss score, so lower is better).

## Techniques Used
- CNN
- Transfer learning
- Noise reduction filters
- Data augmentation
- k-fold cross validation

## Files
- Explore_v3.ipynb: Jupyter notebook with exploratory data analysis and visualizations.
- Iceberg_CNN_model_v4.4.ipynb: Jupyter nobtebook with data augmentation and CNN modeling.
- MLE ND capstone project.pdf: Final project write up.
- README.md: This file.
- proposal.pdf: Capstone project proposal.

## Prerequisites
- pandas
- numpy
- matplotlib
- seaborn
- scipy
- sklearn
- Tensorflow
- Keras
- Tensorboard
