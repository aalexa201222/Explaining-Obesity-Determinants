# Obesity Determinants Analysis Using Explainable Machine Learning Models

## Overview
Obesity is a significant global public health challenge, with its prevalence increasing in many countries. Understanding the factors contributing to different obesity levels is crucial for developing effective interventions. This project explores various explainability methods applied to machine learning models to identify key features influencing obesity levels in individuals from Colombia, Peru, and Mexico.

We implemented several models, including Decision Trees, Random Forests, LightGBM, RuleFit, Neural Networks, and Explainable Boosting Machines (EBM). The project focuses on explaining these models' predictions, offering actionable insights that can guide interventions and policies to improve public health outcomes.

## Key Features
- **Transfer Learning**: Utilizes pre-trained models to improve learning efficiency and effectiveness.
- **Optical Flow Integration**: Employs optical flow to capture motion information from videos, enhancing the model's ability to recognize dynamic actions.
- **Two-stream Network**: Combines spatial and temporal data streams to create a robust model for action recognition.

## Datasets
The dataset used for this project is the "Estimation of obesity levels based on eating habits and physical condition" from the UCI Machine Learning Repository. It includes 17 attributes such as age, gender, family history of overweight, and frequency of physical activity, which are used to classify individuals into one of seven obesity levels.

## Models Implemented
**1. Decision Trees:** A simple, interpretable model that helps understand the relationships between features and obesity levels.

**2. Random Forests:** An ensemble method that improves accuracy by combining multiple decision trees.

**3. LightGBM:** A gradient boosting framework known for efficiency and speed, especially on large datasets.

**4. RuleFit:** Combines ensemble methods with linear models to generate interpretable rules.

**5. Neural Networks:** A feed-forward neural network used for classification tasks.

**6. Explainable Boosting Machines (EBM):** Provides both local and global explanations, combining linear model interpretability with decision tree flexibility.

## Explainability Techniques
- **Feature Importance:** Visualized for models like LightGBM and Random Forests to understand the influence of each feature.
- **Partial Dependence Plots (PDP):** Used to demonstrate the relationship between individual features and obesity levels.
- **Counterfactual Explanations:** Generated using the DiCE library to explore how small changes in features could alter obesity outcomes.
- **Model Pruning:** Applied to Decision Trees to improve interpretability by reducing complexity.
## Installation
Clone the repository to your local machine:
git clone [[https://github.com/aalexa201222/Explaining-Obesity-Determinants.git](https://github.com/aalexa201222/Explaining-Obesity-Determinants)]

## Contributors
[Andreas Alexandrou](https://www.linkedin.com/in/andreas-alexandrou-056528242) <br />
Sotiris Zenios  <br />
Nicolas Stavrou
