# Intrusion-Detection-ML-NSL-KDD
An AI-powered Intrusion Detection System (IDS) trained on the NSL-KDD dataset using Random Forest. Deployed via Google Colab.
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_USERNAME/Intrusion-Detection-ML-NSL-KDD/blob/main/IDS_Implementation.ipynb)
# 🛡️ Network Intrusion Detection using Machine Learning
A high-performance IDS model trained on the NSL-KDD dataset, deployed via Google Colab.

## 🚀 Quick Start
Click the button below to run the full pipeline in your browser:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_USERNAME/YOUR_REPO_NAME/blob/main/IDS_Implementation.ipynb)

## 📊 Dataset Overview
This project uses the **NSL-KDD** dataset, an improved version of KDD'99. 
- **Features:** 41 network traffic attributes.
- **Classes:** Normal vs. Malicious (DoS, Probe, R2L, U2R).



## 🛠️ Methodology
1. **Preprocessing:** Handled categorical variables using Label Encoding.
2. **Model:** Utilized **Random Forest Classifier** for its ability to handle high-dimensional network data without overfitting.
3. **Hardware:** Trained in the cloud using Google Colab to save local system resources.

## 📈 Performance
- **Accuracy:** ~99% on Training Set / ~98% on Test Set.
- **Precision/Recall:** High F1-score for DoS and Probe attacks.
