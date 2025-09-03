# 📩 SMS Spam Detector

A machine learning project that classifies SMS messages as **Spam** or **Not Spam** using Logistic Regression in Python.

## 🎯 Project Overview

This project implements a binary classification model to detect spam messages in SMS text data. The model uses logistic regression with bag-of-words feature extraction to achieve high accuracy in spam detection.

## 🚀 Features

- **High Accuracy**: Achieves 95%+ accuracy on test dataset
- **Real-time Prediction**: Interactive user input for instant spam classification
- **Data Visualization**: Confusion matrix and performance metrics visualization
- **Easy to Use**: Simple command-line interface for testing custom messages

## 🛠️ Technologies Used

- **Python 3.x**
- **Libraries:**
  - `pandas` - Data manipulation and analysis
  - `numpy` - Numerical computing
  - `scikit-learn` - Machine learning algorithms
  - `matplotlib` - Data visualization
  - `seaborn` - Statistical data visualization

## 📊 Dataset

- **Source**: SMSSpamCollection dataset
- **Size**: 5,572 SMS messages
- **Format**: Tab-separated text file
- **Labels**: 
  - `ham` (0) - Legitimate messages
  - `spam` (1) - Spam messages

## 🏗️ Model Architecture

1. **Text Preprocessing**: CountVectorizer for bag-of-words representation
2. **Algorithm**: Logistic Regression with binary classification
3. **Train-Test Split**: 80% training, 20% testing
4. **Evaluation Metrics**: Accuracy, Precision, Recall, F1-score
