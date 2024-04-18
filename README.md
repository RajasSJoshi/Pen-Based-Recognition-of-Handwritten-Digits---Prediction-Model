# Pen-Based Recognition of Handwritten Digits

This repository contains code and resources for the Pen-Based Recognition of Handwritten Digits project using PyCaret for classification. The dataset used for this project is the "Pen-Based Recognition of Handwritten Digits" dataset.

## Introduction

Handwriting recognition has been a challenging problem in the field of pattern recognition and machine learning. In this project, we explore the application of machine learning algorithms to recognize handwritten digits using the Pen-Based Recognition dataset.

## Dataset

The dataset consists of handwritten digits collected from various individuals. Each digit is represented by 16 attributes. The dataset is split into training and testing sets, which are loaded and processed using Pandas.

## Setup

We begin by importing necessary libraries and loading the dataset into Pandas dataframes. 

## PyCaret Setup

PyCaret is used for streamlined machine learning experiments. We set up PyCaret with the training data and identify the best-performing model using the `compare_models` function.

## Model Training and Evaluation

The best model identified by PyCaret is trained on the full dataset and evaluated using various metrics, including confusion matrix, ROC curve, and class distribution of predictions.

## Save Model

Finally, the best-performing model is saved for future use.


## References
https://archive.ics.uci.edu/dataset/81/pen+based+recognition+of+handwritten+digits


