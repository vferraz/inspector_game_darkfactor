# Understanding Dark Personality Traits and Strategic Choices in an Inspection Game: Insights from Machine Learning and Causal Inference

Reproduction Package

This repository contains data analysis, machine learning models, and causal machine learning models for a research project investigating the influence of the Dark Factor in strategic decision-making within Inspector games.

## Contents
- Raw experimental data: `data/`
- Raw data processing script: `reproduction_package/data_processing.iypnb`
- Statistical analysis script: `reproduction_package/statistical_analysis.ipynb`
- Random forest models: `reproduction_package/random_forest_analysis.ipynb`
- Causal forest models: `reproduction_package/causal_forest.ipynb`. The models were fine-tuned using grid search and are stored as pipelines for ease of use.
  - `reproduction_package/ml_models/`: First stage models for causal analysis, saved as `.joblib` files.
  - `reproduction_package/dml_models/`: Second stage Double Machine Learning (DML) models, also saved as `.joblib` files for easy replication and deployment.
 
The project aims to provide a comprehensive resource for exploring the nuances of strategic decision-making influenced by personality traits.




