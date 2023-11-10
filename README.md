# Sentiment Analysis for Financial News Project

Chua Yong Xuan, Daniel Yang, Jiang Zixing

This project focuses on performing sentiment analysis on financial news using deep learning models, specifically BERT (Bidirectional Encoder Representations from Transformers) and XLNet. The dataset was sourced from Kaggle's Sentiment Analysis for Financial News dataset.

## Project Structure

The project is organized into two main directories: Data Preprocessing and Models, along with a comprehensive project report.

### Data Preprocessing

This directory contains the initial dataset and the Jupyter notebook used for data preprocessing and augmentation.

- `all-data.csv`: Original dataset obtained from Kaggle.
- `NN_Project_2_Data_Processing.ipynb`: Jupyter notebook detailing the steps taken for data preprocessing and augmentation.

### Models

This directory includes Jupyter notebooks for the BERT and XLNet models, along with various datasets created through data augmentation and the standard train-validation-test split.

- `NN_Project_2_BERT.ipynb`: Jupyter notebook for sentiment analysis using the BERT model.
- `NN_Project_2_XLNet.ipynb`: Jupyter notebook for sentiment analysis using the XLNet model.
- `gpt-augment-train.csv`: Training set augmented using GPT-2.
- `nlpaug-train.csv`: Training set augmented using nlpaug.
- `google-translate-train.csv`: Training set augmented using Google Translate.
- `train.csv`: Standard training set.
- `validation.csv`: Validation set.
- `test.csv`: Test set.

### NN Project Report

- `NN Project Report.pdf`: A comprehensive report detailing the methodologies, experiments, results, and conclusions of the project.

