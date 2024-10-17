# AIPI-XAI-Explainable-AI-II

This project demonstrates the use of Explainable AI (XAI) techniques to interpret a Random Forest model trained on the **California Housing dataset**. The goal is to explore global and local feature contributions to predictions using **PDP**, **ICE**, and **ALE** plots.

## Features
- **Partial Dependence Plot (PDP)**: Shows the global effect of a feature on predictions.
- **ICE Plot**: Reveals individual prediction variability.
- **Accumulated Local Effects (ALE)**: Highlights local feature interactions.
- **Permutation Feature Importance**: Identifies key features contributing to model accuracy.
- **Model Evaluation**: Metrics like **R²** and **MSE** assess model performance.

## Dataset
The **California Housing dataset** from `sklearn.datasets`.

## Requirements
- Python 3.x
- Libraries: `numpy`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn`, `alepython`, `shap`

## Instructions
1. Clone the repository.
2. Install dependencies with:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter notebook on Google Colab or locally.

## Results
- **R²**: 0.805
- **MSE**: 0.255
- Key insights on how median income and other features influence housing prices.

## License
This project is licensed under the MIT License.

---

This README provides a concise yet comprehensive guide for your GitHub project.
