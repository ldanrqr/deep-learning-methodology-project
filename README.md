# Deep Learning Methodology Project

## Overview
This project analyzes the impact of different deep learning methodologies on classification performance.

## Methods Used
- Activation Functions: ReLU vs Sigmoid
- Optimizers: Adam vs SGD
- Regularization: Dropout

## Dataset
Breast Cancer dataset from sklearn.

# Results

| Model | Average Accuracy |
|------|----------------|
| ReLU + Adam | 0.95 |
| Sigmoid + Adam | 0.64 |
| ReLU + SGD | 0.71 |
| ReLU + Adam + Dropout | 0.95 |

## Key Findings
- ReLU outperforms Sigmoid
- Adam is more stable than SGD
- Dropout improves generalization

## How to Run
Open the notebook (.ipynb) file in Google Colab and run all cells.
