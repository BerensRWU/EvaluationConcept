# Sensitivity Analysis and Multifactorial Performance Evaluation

This repository provides a set of tools for conducting sensitivity analysis and multifactorial performance evaluation on machine learning models, specifically in the context of sensor data (LiDAR and RADAR). The scripts allow for the evaluation of model robustness under various disturbance types and levels.

### Multifactorial Performance Evaluation

The multifactorial_performance function evaluates model performance across multiple pretrained models, disturbances, and levels, and generates comparative plots.

The function will generate plot images like this:
<img src="https://github.com/BerensRWU/EvaluationConcept/blob/main/images/beide_add_random_noise.png" width="400" height="400">

### Sensitivity Analysis

The `sensitivity_analysis` function evaluates the model's performance across various disturbances and levels. This can help in understanding how different types of sensor disturbances affect model accuracy.

The function will generate plot images like this:
<img src="https://github.com/BerensRWU/EvaluationConcept/blob/main/images/no_fusion.png" width="400" height="400">

