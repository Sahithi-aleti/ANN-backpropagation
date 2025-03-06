# ANN-backpropagation
# Kidney Disease Classification using Neural Network

## Overview
This project implements a neural network from scratch to classify kidney disease using medical data. The model includes preprocessing, feature encoding, and normalization.

## Dataset Processing
- **Missing Values**: Filled with mode (categorical) or median (numerical).
- **Feature Encoding**: Label encoding for categorical features.
- **Normalization**: StandardScaler applied to numerical features.
- **Train-Test Split**: 80% training, 20% testing.

## Neural Network Architecture
- **Input Layer**: Number of features.
- **Hidden Layers**: 64 and 32 neurons with Leaky ReLU.
- **Output Layer**: Softmax activation.

## Optimization Techniques
- Batch Normalization, Dropout, L2 Regularization, and He Initialization.

## Training Details
- **Optimizer**: Gradient Descent
- **Loss Function**: Approximate Mean Squared Error
- **Epochs**: 100, **Learning Rate**: 0.002

## Results
- **Training Accuracy**: 97.81%
- **Test Accuracy**: 96.25%

## Usage
1. Install dependencies:
   ```bash
   pip install numpy pandas scikit-learn
   ```
2. Place `kidney_disease_dataset.csv` in the working directory.
3. Run the script:
   ```bash
   python neural_network.py
   ```


