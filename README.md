# Credit_card_fraud
# Fraud Detection Using Hybrid Deep Learning Model

## Overview
This project focuses on detecting fraudulent transactions using a hybrid deep learning approach. It combines a Multi-Layer Perceptron (MLP) and an Autoencoder to improve fraud detection performance.

## Dataset
- **Source**: [Kaggle - Fraud Detection Dataset](https://www.kaggle.com/datasets/kartik2112/fraud-detection)
- The dataset contains credit card transactions, labeled as fraud (`is_fraud = 1`) or genuine (`is_fraud = 0`).

## Project Structure
📂 fraud-detection │── 📜 fraud_detection.ipynb # Jupyter Notebook with the complete workflow │── 📜 README.md # Project documentation │── 📜 requirements.txt # List of required dependencies

bash
Copy
Edit

## Installation
Clone the repository and install dependencies:

```sh
git clone https://github.com/DYNAMO_PENTESTER/fraud-detection.git
cd fraud-detection
pip install -r requirements.txt
Steps in the Notebook
Data Preprocessing

Load dataset and remove unnecessary columns

Encode categorical variables

Normalize numerical features

Handle class imbalance using SMOTE

Model Training

MLP Model: A deep learning model trained with fraud labels

Autoencoder: An unsupervised model trained on normal transactions to detect anomalies

Hybrid Model for Fraud Detection

Combines predictions from MLP and Autoencoder for better fraud detection

Evaluation & Visualization

Performance metrics: Accuracy, Confusion Matrix, ROC AUC Score

Feature importance analysis using SHAP

Precision-Recall curve for model evaluation

Results
The hybrid model improves fraud detection accuracy by combining two approaches.

Precision-Recall curve analysis shows improved performance over a standalone MLP.

How to Run
Execute the Jupyter Notebook step by step:

sh
Copy
Edit
jupyter notebook fraud_detection.ipynb
Future Improvements
Fine-tuning hyperparameters for better results

Exploring other anomaly detection techniques

Enhancing feature engineering for better fraud detection

🚀 Author
Dynamo
