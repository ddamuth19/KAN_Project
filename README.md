#Deep Learning in Bioinformatics Using Kolmogorov–Arnold Networks

Dawson Damuth, Erin Gregoire, and Daniel Viola

This project explores the use of Kolmogorov–Arnold Networks (KANs) for predicting the presence of diabetes from patient health indicators. Unlike traditional “black box” neural networks, KANs leverage adaptive spline activations to provide both strong predictive performance and interpretability, revealing how specific features (e.g., BMI, blood pressure, glucose levels) influence predictions.

Our goals were twofold:

Accuracy: Achieve >85% classification accuracy in predicting diabetes.

Interpretability: Identify and visualize the most influential health indicators driving predictions.

The model was implemented in PyTorch, trained from scratch, and optimized through techniques such as dropout, early stopping, and learning rate scheduling. Performance was evaluated using accuracy, ROC-AUC, precision, recall, F1-score, and confusion matrices, with results benchmarked against a standard multilayer perceptron (MLP).

By combining high accuracy with transparency, this work demonstrates how interpretable deep learning models like KANs can enhance clinical decision support systems—enabling healthcare providers to deliver more personalized treatment and empowering patients to better understand their health risk factors.

Dataset: Diabetes Health Indicators Dataset (Kaggle, 2022)

Reference: KAN: Kolmogorov–Arnold Networks (Liu et al., 2024)
 
