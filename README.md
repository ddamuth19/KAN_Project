# Deep Learning in Bioinformatics Using Kolmogorov–Arnold Networks

A Kolmogorov–Arnold Network (KAN) is a state-of-the-art deep learning model that improves interpretability compared to traditional Multi-Layer Perceptrons (MLPs). In this project, our team of three built and evaluated a custom KAN to detect diabetes from health indicator data. The goal was to deliver both high predictive accuracy and transparent feature explanations, making the model suitable for clinical decision support and healthcare research.

### Skills Applied:

- Deep learning model development in PyTorch

- Hyperparameter tuning, dropout regularization, early stopping

- Model interpretability & spline activation visualization

- Comparative analysis with baseline models (MLP, official KAN)

- LLM integration for result explanation

### Dataset:
[Diabetes Health Indicators Dataset (Kaggle, 2022)](https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset)

### Methodology:

- Built, trained, and optimized a custom KAN from scratch in PyTorch

- Implemented baseline models: standard MLP and official KAN reference implementation

- Conducted comparative performance evaluations across all models

- Enhanced interpretability with spline activation visualizations and LLM-based explanations

### Tools & Technologies:

- Programming Language: Python

- Libraries: torch, sklearn, pandas, matplotlib, openai, kagglehub

- Software: Jupyter Notebook
 
### Results & Evaluation:

- Achieved 86% accuracy and 0.31 loss with both the custom KAN and MLP

- KAN revealed BMI, glucose levels, and blood pressure as top predictors, providing actionable interpretability

- Official KAN reference model underperformed (73% accuracy), but highlighted alternative factors such as stroke history and income level

- Demonstrated KAN’s ability to pair competitive accuracy with explainability, crucial for healthcare adoption

### Challenges & Learning:

- Engineered KAN’s learnable spline activations from standard MLP weight vectors

- Developed new visualization methods for activation functions and feature importance

- Strengthened expertise in model interpretability, comparative evaluation, and optimization strategies

### Contribution:

- Team Members: Dawson Damuth, Erin Gregoire, and Daniel Viola

- My Role:

  - Designed and implemented the LLM results interpreter

  - Contributed to hyperparameter tuning and model optimization

  - Assisted in comparative evaluation against MLP and official KAN models
 
 

Reference: [KAN: Kolmogorov–Arnold Networks (Liu et al., 2024)](https://arxiv.org/abs/2404.19756)
 
