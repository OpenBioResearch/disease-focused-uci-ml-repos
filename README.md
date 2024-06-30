# uci-ml-clinical-explorations

## Project Overview

This repo contains two Jupyter notebooks which analyze clinicopathologic features related to two distinct diseases:  thyroid cancer recurrence and glioma grading.  Both projects leverage machine learning models to identify critical factors influencing disease outcomes. These Jupyter notebooks were created using Google Colab.

## Notebooks

1. **Thyroid Cancer Recurrence Analysis using CatBoost**:
   - **Notebook**: `thyroid_cancer_catboost.ipynb`
   - **Description**: This notebook leverages the CatBoost gradient boosting library to analyze clinicopathologic features and identify the most critical factors influencing thyroid cancer recurrence.
   - **Dataset**: [Differentiated Thyroid Cancer Recurrence](https://archive.ics.uci.edu/ml/datasets/Differentiated+Thyroid+Cancer+Recurrence) from the UCI Machine Learning Repository.

2. **Glioma Grading using PyTorch**:
   - **Notebook**: `uci_glioma_grading.ipynb`
   - **Description**: This notebook uses a PyTorch-based neural network model with early stopping to analyze feature importance for glioma grading.
   - **Dataset**: [Glioma Grading Clinical and Mutation Features Dataset](https://archive.ics.uci.edu/dataset/759/glioma+grading+clinical+and+mutation+features+dataset) from the UCI Machine Learning Repository.

## Setup

To install the ucimlrepo package and dataset you may either access the dataset in the notebooks in above step or follow the instructions below:

In a Jupyter notebook, install ucimlrepo package with the command:

```bash
!pip install -r requirements.txt
!pip install -U ucimlrepo 
```

Import the thyroid recurrence dataset:

```python
from ucimlrepo import fetch_ucirepo 

# fetch dataset 
differentiated_thyroid_cancer_recurrence = fetch_ucirepo(id=915) 
	
# data (as pandas dataframes) 
X = differentiated_thyroid_cancer_recurrence.data.features 
y = differentiated_thyroid_cancer_recurrence.data.targets 
	
# metadata 
print(differentiated_thyroid_cancer_recurrence.metadata) 
	
# variable information 
print(differentiated_thyroid_cancer_recurrence.variables) 
```
Import the glioma grading dataset:

```python
from ucimlrepo import fetch_ucirepo 
  
# fetch dataset 
glioma_grading_clinical_and_mutation_features = fetch_ucirepo(id=759) 
  
# data (as pandas dataframes) 
X = glioma_grading_clinical_and_mutation_features.data.features 
y = glioma_grading_clinical_and_mutation_features.data.targets 
  
# metadata 
print(glioma_grading_clinical_and_mutation_features.metadata) 
  
# variable information 
print(glioma_grading_clinical_and_mutation_features.variables) 
```

## License

This dataset is licensed under a Creative Commons Attribution 4.0 International (CC BY 4.0) license.
