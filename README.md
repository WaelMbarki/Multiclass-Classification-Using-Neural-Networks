# Multiclass Classification Using Neural Networks

## Table of Contents

- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Tools](#tools)
- [Steps](#steps)

### Project Overview

The aim of this project is to build a neural network model for multiclass classification using a synthetic dataset of blobs. Each data point belongs to one of several clusters, and the goal is to classify these points into their respective categories based on the features provided.

### Data Source

**Blobs Dataset**: A synthetic dataset generated using the `make_blobs` function from `sklearn.datasets`. This dataset consists of multiple clusters of points, where each cluster represents a different class for the classification task.

### Tools

- **Jupyter Notebook**: An interactive environment for running Python code. You can [download it here](https://www.anaconda.com/download/).
- **Python Libraries**:
  - `scikit-learn`: For generating the dataset and splitting it into training and test sets.
  - `matplotlib` or `seaborn`: For visualizing the data.
  - `PyTorch` : For building and training the neural network.
  - 'Numpy' : For data manipulation

### Steps

1. **Data Generation**: Generate the dataset using `make_blobs` from `sklearn.datasets`.
2. **Data Splitting**: Split the data into training and test sets.
3. **Data Visualization**: Visualize the dataset to understand the distribution of the blobs.
4. **Model Building**: Build a neural network for multiclass classification.
5. **Model Training**: Train the neural network on the training dataset.
6. **Model Evaluation**: Evaluate the performance of the trained model on the test set.
7. **Prediction and Visualization**: Make predictions on the test set and visualize the results.
