# Artificial Neural Networks – Learning Notes

This repository contains my learning and practice notebook for Artificial Neural Networks (ANNs) using TensorFlow/Keras.

## Concepts Covered
- Data preprocessing for neural networks
- One-hot encoding
- Feature scaling
- Train-test split
- ANN using Keras Sequential API
- Hidden layers & activation functions
- Dropout regularization
- Binary classification
- Early stopping
- Model evaluation & visualization

## Dataset
Customer Churn dataset

## Files
- `ANN_Learning_Notes.ipynb` – Main learning notebook

## Observations
- Although the model achieved ~79% accuracy, the confusion matrix revealed that it was biased toward predicting the majority class, showing that accuracy alone is not a reliable metric for imbalanced datasets.
- Implementing feature scaling significantly stabilized training and improved convergence speed of the ANN.
- Early stopping helped prevent unnecessary training epochs and reduced the risk of overfitting.
- Dropout regularization slightly reduced training accuracy but improved validation stability, highlighting the trade-off between bias and variance.
- This exercise clarified how ANN performance is highly sensitive to preprocessing choices such as encoding and scaling.

## Future Improvements
- Handle class imbalance
- Tune hyperparameters
- Add ROC-AUC and precision-recall curves

