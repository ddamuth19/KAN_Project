# Deep Learning in Bioinformatics Using Kolmogorov–Arnold Networks

A Kolmogorov–Arnold Network (KAN) is a state-of-the-art deep learning model that improves interpretability compared to traditional Multi-Layer Perceptrons (MLPs). In this project, our team of three designed and evaluated a custom KAN to detect diabetes in patients using health indicator data. The goal was to achieve strong predictive performance while providing transparent explanations of feature importance, a critical aspect for healthcare applications.

### Skills:
PyTorch, Hyperparameter Tuning, Regularization (Dropout, Early Stopping), Model Interpretability, Comparative Analysis, LLM Integration

### Dataset:
[Diabetes Health Indicators Dataset (Kaggle, 2022)](https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset)

### Methodology:

- Built, trained, and optimized a custom KAN from scratch in PyTorch.

- Implemented baseline models: a standard MLP and the official KAN reference implementation.

- Conducted comparative performance evaluation across all models.

- Visualized spline activations in conjunction with an LLM to explain feature contributions to predictions.

### Tools & Technologies:

- Programming Language: Python

- Libraries: torch, sklearn, pandas, matplotlib, openai, kagglehub

- Software: Jupyter Notebook
 
### Results & Evaluation:

- Both the custom KAN and MLP achieved 86% accuracy and 0.31 loss on the test dataset.

- KAN offered superior interpretability, identifying BMI, glucose levels, and blood pressure as top predictors of diabetes.

- The official KAN reference model achieved 73% accuracy but emphasized different key indicators. (e.g., stroke history, physical activity, income level)

- Findings highlight KAN’s ability to combine competitive performance with transparent feature importance, making it suitable for healthcare decision support.

### Challenges & Learning:

- Adapting MLP weight vectors into KAN’s learnable spline activations required extensive experimentation

- Gained experience in visualizing learned activation functions and model internals

- Strengthened skills in comparative evaluation, interpretability, and regularization strategies in deep learning models

### Contribution:

- Team Members: Dawson Damuth, Erin Gregoire, and Daniel Viola

My Role:

- Designed and implemented the LLM results interpreter

- Contributed to hyperparameter tuning and model optimization

- Assisted in comparative evaluation against MLP and official KAN models

Reference: [KAN: Kolmogorov–Arnold Networks (Liu et al., 2024)](https://arxiv.org/abs/2404.19756)
 
