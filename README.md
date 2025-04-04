# Customer Churn Prediction using Artificial Neural Networks (ANN)

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange)
![scikit-learn](https://img.shields.io/badge/scikit--learn-1.0%2B-green)
![Streamlit](https://img.shields.io/badge/Streamlit-1.12%2B-red)

A deep learning solution for predicting customer churn using Artificial Neural Networks, deployed as an interactive web application.

## Table of Contents
- [Project Overview](#project-overview)
- [Key Features](#key-features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Model Architecture](#model-architecture)
- [Results](#results)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)

## Project Overview
This project predicts customer churn probability for a banking/financial services scenario using:
- Artificial Neural Network (ANN) with 3 hidden layers
- Feature engineering including scaling and categorical encoding
- Interactive prediction interface via Streamlit

## Key Features
✔ Preprocessing pipeline handling numerical and categorical features  
✔ ANN model with dropout layers for regularization  
✔ Hyperparameter tuning with Keras Tuner  
✔ Model evaluation metrics (Accuracy, Precision, Recall, AUC-ROC)  
✔ Interactive web interface for real-time predictions  

## Tech Stack
**Core ML:**
- TensorFlow/Keras
- scikit-learn
- Pandas/Numpy

**Deployment:**
- Streamlit (frontend)
- Pickle (model serialization)

**Development:**
- Jupyter Notebook (EDA + prototyping)
- Visual Studio Code

## Installation
1. Clone the repository:
```bash
git clone https://github.com/Saurabh311/ANN-Classification-Churn.git
cd ANN-Classification-Churn

