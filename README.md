# 🏦 Customer Churn Prediction using ANN

[![Open in Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://ann-classification-churn-h3fsvuqsdwcsysn6tfvhyi.streamlit.app/)
![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange)
![Accuracy](https://img.shields.io/badge/Accuracy-86%25-brightgreen)

**Live Demo:** [Try the Churn Predictor](https://ann-classification-churn-h3fsvuqsdwcsysn6tfvhyi.streamlit.app/)

A production-ready deep learning solution for predicting banking customer churn, featuring:
- Artificial Neural Network (ANN) with dropout regularization
- Interactive web interface with real-time predictions
- Comprehensive model evaluation metrics

## 🚀 Quick Start

### Option 1: Use the Live App
Simply visit the [deployed application](https://ann-classification-churn-h3fsvuqsdwcsysn6tfvhyi.streamlit.app/) and input customer data.

### Option 2: Local Installation
```bash
git clone https://github.com/Saurabh311/ANN-Classification-Churn.git
cd ANN-Classification-Churn
pip install -r requirements.txt
streamlit run app.py


### 🧠 Model Architecture
Model: "sequential"
┌─────────────────────────────────┐
│ Layer (type)       Output Shape │
├─────────────────────────────────┤
│ dense (Dense)      (None, 16)   │
│ dropout (Dropout)  (None, 16)   │
│ dense_1 (Dense)    (None, 16)   │
│ dense_2 (Dense)    (None, 1)    │
└─────────────────────────────────┘
Total params: 577 | Trainable params: 577

### 📊 Performance Metrics
Metric	Training	Validation
Accuracy	86.2%	85.7%
Precision	0.81	0.80
Recall	0.72	0.71
AUC-ROC	0.89	0.88
💡 Key Features
Dynamic Input Handling: Processes both numerical and categorical features

Risk Visualization: Displays churn probability with interpretable metrics

Responsive Design: Works on desktop and mobile devices

### 🛠️ Tech Stack
Category	Technologies
Core ML	TensorFlow, Keras, scikit-learn
Frontend	Streamlit
Processing	Pandas, NumPy
Deployment	Streamlit Cloud
