# HateSpeechFilter-
# Hate Speech Detection in Social Media

This repository contains a machine learning project aimed at detecting hate speech on social media platforms. By analyzing textual data classified as hate speech (1) or not hate speech (0), this project employs logistic regression and data reduction techniques to develop a predictive model.

## Project Overview

The increase in hate speech on social media platforms necessitates sophisticated detection tools. This project addresses this need by utilizing advanced data processing techniques and machine learning algorithms to improve the detection and analysis of hate speech.

## Features

- **Data Processing**: Implementation of PCA for data reduction and efficient handling of high-dimensional data.
- **Logistic Regression**: Utilization of logistic regression for binary classification of text data into hate speech or not.
- **Performance Metrics**: Evaluation of model performance using the F1 score.
- **Visualization**: Graphs plotting the performances of the logistic regression model across various learning rates.

## Setup

To run this project, ensure that Python 3 and the following packages are installed:
- numpy
- matplotlib
- scikit-learn
- pandas

You can install them using pip:

```bash
pip install numpy matplotlib scikit-learn pandas
```
## Usage

### Data Preparation
Scripts are provided to perform PCA on the dataset and prepare it for the modeling steps.

### Logistic Regression Model
- Train the logistic regression model using the provided scripts.
- Evaluate the model using the F1 score and plot performance graphs based on different learning rates.

