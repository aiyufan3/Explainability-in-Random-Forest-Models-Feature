# AIPI-XAI-Explainable-AI-II

This project demonstrates using **Explainable AI (XAI)** techniques to interpret a Random Forest model trained on the **Forest Cover dataset**. The goal is to understand global and local feature contributions to forest cover type predictions using **PDP**, **ICE**, and **ALE** plots.

## Features
- **Partial Dependence Plot (PDP)**: Visualizes the global effect of a feature (e.g., elevation) on predictions.
- **ICE Plot**: Shows individual prediction variability, highlighting how predictions change for specific instances.
- **Accumulated Local Effects (ALE)**: Captures local feature interactions and dependencies, providing a more granular view of feature impacts.
- **Permutation Feature Importance**: Identifies the most influential features, such as elevation and distance to hydrology, that drive model predictions.
- **Model Evaluation**: Metrics like **R²** and **MSE** assess model performance and interpretability.

## Dataset
The **Forest Cover dataset** is sourced from `sklearn.datasets` or **OpenML**. It contains environmental and spatial features to classify forest cover types.

## Requirements
- Python 3.x
- Libraries: `numpy`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn`, `alibi`, `shap`

## Instructions
1. Clone the repository.
2. Install dependencies with:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter notebook on Google Colab or locally to view the results and analysis.

## Results
- **R²**: 0.488
- **MSE**: 0.953
- Key insights on how features like elevation, aspect, and distance to hydrology influence forest cover predictions.

## License
This project is licensed under the MIT License.
