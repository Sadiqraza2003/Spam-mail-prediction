# Spam Mail Prediction Model

This repository contains a Spam Mail Prediction Model built using a Logistic Regression model. The project was developed on Google Colab using Python, along with libraries such as NumPy and Pandas.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)

## Introduction

Spam mail detection is a crucial aspect of email management, helping to filter out unwanted and potentially harmful messages. This project implements a Logistic Regression model to predict whether an email is spam or not. The model is trained and tested on a dataset of emails, utilizing various features extracted from the email content.

## Dataset

The dataset used in this project consists of emails labeled as spam or not spam. Each email is represented by a set of features that are used to train the Logistic Regression model.

## Installation

To run this project locally, you'll need to have Python installed along with the necessary libraries. Follow the instructions below to set up your environment:

1. Clone this repository:
    ```sh
    git clone https://github.com/your-username/spam-mail-prediction.git
    cd spam-mail-prediction
    ```

2. Install the required libraries:
    ```sh
    pip install numpy pandas scikit-learn
    ```

## Usage

To use the model, follow these steps:

1. Open the Google Colab notebook provided in this repository: [Spam_Mail_Prediction_Model.ipynb](https://colab.research.google.com/drive/14_sO8LKvO0icgmU-Qhl-Yi3Yggc8dOKB?usp=sharing).
2. Upload the dataset to your Google Colab environment.
3. Run the cells in the notebook to preprocess the data, train the model, and evaluate its performance.

Here's a brief overview of the steps involved:

- **Data Preprocessing**: Load the dataset and preprocess it (e.g., handling missing values, feature extraction).
- **Model Training**: Train the Logistic Regression model on the preprocessed data.
- **Model Evaluation**: Evaluate the model's performance using metrics such as accuracy, precision, recall, and F1-score.

## Results

The Logistic Regression model achieves the following performance on the test set:

- **Accuracy**:  0.9659192825112107


These metrics indicate the model's effectiveness in predicting spam emails.


