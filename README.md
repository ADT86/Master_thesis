# Master Thesis Pipeline README

## Overview
This pipeline, developed as part of a master's thesis, provides a comprehensive framework for preprocessing, model training, evaluation, and results storage. It is particularly tailored for datasets and tasks that may require handling class imbalances and utilizing latent space representations.

## Key Features

### 1. **Comprehensive Imports**
- The pipeline integrates with various essential Python libraries, including but not limited to:
  - Scikit-learn: For various machine learning tasks.
  - TensorFlow: For deep learning functionalities.
  - XGBoost: Gradient boosted decision trees.
  - Imbalanced-learn: For addressing class imbalance in datasets.

### 2. **Reproducibility**
- A `set_seed` utility ensures reproducibility across different runs by setting seeds for random processes.

### 3. **Data Preprocessing**
- The pipeline offers a robust preprocessing function that:
  - Drops duplicates.
  - Imputes missing values.
  - Provides dataset-specific preprocessing steps.

### 4. **Results Management**
- The pipeline can store the results of model evaluations in a JSON format, facilitating easy access and post-hoc analysis.
- It also offers functionality to load and parse these results for further analysis.

### 5. **Metrics Calculation**
- Comprehensive functions are available for calculating various performance metrics.
- The pipeline can handle evaluations for both traditional classifiers and those that use latent spaces (like Variational Autoencoders or similar models).

## Usage

1. Ensure all the required libraries are installed.
2. Load your dataset and adapt the preprocessing function if necessary.
3. Train your desired models and evaluate their performance.
4. Store and analyze results as needed.

## Dependencies
- Scikit-learn
- TensorFlow
- XGBoost
- Imbalanced-learn
- And others as listed in the code.

## Notes
- As with all pipelines, users are advised to thoroughly test the pipeline with their specific datasets and possibly make adjustments to better suit their needs.
