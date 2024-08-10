# Comment Toxicity Predictor

This project is a Comment Toxicity Predictor built for the Kaggle competition on toxic comment classification. The goal of this project is to create a model that can identify and classify toxic comments into various categories such as toxic, severe toxic, obscene, threat, insult, and identity hate.

## Project Overview

The Comment Toxicity Predictor utilizes deep learning techniques to analyze and classify text comments. The model is based on TensorFlow and Keras, leveraging text vectorization and LSTM (Long Short-Term Memory) layers to process and predict the toxicity of comments.

### Features

- **Text Vectorization:** Converts text comments into numerical representations that the model can process.
- **Bidirectional LSTM:** Captures dependencies in text by processing sequences in both forward and backward directions.
- **Multi-label Classification:** Predicts multiple toxicity labels simultaneously.

## Dataset

The dataset used for training the model is from the [Jigsaw Toxic Comment Classification Challenge](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge). It contains a variety of comments labeled with different toxicity categories.

## Installation

To get started, you need to install the required Python packages. You can do this using pip:

```bash
pip install tensorflow pandas numpy scikit-learn matplotlib ipywidgets
