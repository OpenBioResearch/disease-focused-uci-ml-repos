
# Clinicopathologic Feature Analysis

This repository contains Jupyter notebooks for analyzing clinicopathologic features related to two distinct diseases: thyroid cancer recurrence and glioma grading. Both projects leverage machine learning models to identify critical factors influencing disease outcomes. The Jupyter notebooks were created using Google Colab with many dependencies pre-installed.

## Notebooks

1. **Thyroid Cancer Recurrence Analysis using CatBoost**:
   - **Notebook**: `thyroid_cancer_catboost.ipynb`
   - **Description**: This notebook leverages the CatBoost gradient boosting library to analyze clinicopathologic features and identify the most critical factors influencing thyroid cancer recurrence.
   - **Dataset**: [Differentiated Thyroid Cancer Recurrence](https://archive.ics.uci.edu/ml/datasets/Differentiated+Thyroid+Cancer+Recurrence) from the UCI Machine Learning Repository.

2. **Glioma Grading using PyTorch**:
   - **Notebook**: `uci_glioma_grading.ipynb`
   - **Description**: This notebook uses a PyTorch-based neural network model with early stopping to analyze feature importance for glioma grading.
   - **Dataset**: [Glioma Grading Clinical and Mutation Features Dataset](https://archive.ics.uci.edu/dataset/759/glioma+grading+clinical+and+mutation+features+dataset) from the UCI Machine Learning Repository.

## Project Structure

- **thyroid_cancer_catboost.ipynb**: Jupyter notebook for analyzing thyroid cancer recurrence using the CatBoost library.
- **uci_glioma_grading.ipynb**: Jupyter notebook for glioma grading using a neural network model in PyTorch.

## Getting Started

To get started with these notebooks, follow the steps below:

1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   ```

2. **Install necessary dependencies (not for Google Colab users)**:
   - Required libraries:
     - numpy: 1.25.2
     - pandas: 2.0.3
     - matplotlib: 3.7.1
     - seaborn: 0.13.1
     - scikit-learn: 1.2.2
     - tensorflow: 2.15.0
     - torch: 2.3.0+cu121
     - requests: 2.31.0
     - beautifulsoup4: 4.12.3
     - scipy: 1.11.4
     - statsmodels: 0.14.2
     - xgboost: 2.0.3
     - catboost: 1.2.5

3. **Run the notebooks**:
   - Open the notebooks in Jupyter or Google Colab and follow the instructions within each notebook.

## License

This dataset is licensed under a Creative Commons Attribution 4.0 International (CC BY 4.0) license.
