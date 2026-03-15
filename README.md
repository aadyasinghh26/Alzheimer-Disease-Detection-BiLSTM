# Alzheimer Disease Detection using BiLSTM

Hybrid Ensemble Learning and BiLSTM Modeling for Early Alzheimer’s Disease Detection using OASIS Clinical Biomarkers.

## Project Overview
This project predicts early Alzheimer’s disease using machine learning and deep learning models trained on clinical biomarkers from the OASIS dataset.

The goal is to compare traditional machine learning models with a deep learning BiLSTM model to improve prediction accuracy.

## Dataset
OASIS Brain MRI Dataset  
https://www.oasis-brains.org/

## Project Architecture

The following diagram shows the workflow of the hybrid ML–DL framework used for early Alzheimer's disease detection.

![Architecture](architecture.jpeg)

## Models Used
- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost
- Bidirectional LSTM (BiLSTM)

## Techniques Used
- Data preprocessing
- SMOTE class balancing
- Feature scaling
- Deep learning using BiLSTM

## Results

### Confusion Matrix
![Confusion Matrix](data/results/confusion_matrix.png)

### Accuracy & Loss Graph
![Accuracy Loss](data/results/accuracy_loss_graph.png)

### PCA Visualization
![PCA Plot](data/results/pca_plot.png)

## Technologies
Python, TensorFlow, Scikit-learn, Pandas, NumPy, Matplotlib

## How to Run
1. Install dependencies
2. Open the notebook `alzheimers_detection.ipynb`
3. Run all cells to train and evaluate the models
