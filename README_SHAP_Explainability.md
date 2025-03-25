# SHAP Explainability Tutorial: Interpreting ML Predictions with Shapley Values

This tutorial demonstrates how to use SHAP (SHapley Additive exPlanations) to explain predictions made by an XGBoost model on the Breast Cancer Wisconsin dataset. It includes exploratory data analysis (EDA), model training, SHAP value computation, and interpretation through summary, beeswarm, and force plots.

## Files

- shap_explainability_breast_cancer.ipynb: Complete Jupyter notebook with code, SHAP visuals, and educational commentary
- README.md: This file
- requirements.txt: Dependencies to run the notebook

## Dataset

We use the Breast Cancer dataset from `sklearn.datasets`, which includes 569 samples and 30 features related to digitized breast tissue measurements. The task is binary classification (benign or malignant).

## Learning Objectives

- Understand the importance of model explainability in high-stakes ML
- Apply SHAP to decompose individual predictions into feature contributions
- Compare SHAP summary, beeswarm, and force plots for different interpretability goals
- Gain experience with XGBoost, SHAP, and structured data modeling

## How to Run

1. Clone the repository or download the files
2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Launch the notebook:
   ```
   jupyter notebook shap_explainability_breast_cancer.ipynb
   ```

## References

- Lundberg, S. M., & Lee, S.-I. (2017). A Unified Approach to Interpreting Model Predictions. NeurIPS.
- Lundberg, S. M., et al. (2020). From Local Explanations to Global Understanding with Explainable AI for Trees. Nature Machine Intelligence.
- Molnar, C. (2022). Interpretable Machine Learning.
- Pedregosa, F., et al. (2011). Scikit-learn: Machine Learning in Python.

## License

MIT License
