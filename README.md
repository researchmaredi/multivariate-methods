# Multivariate Analysis Portfolio

This repository contains a collection of projects demonstrating advanced multivariate statistical techniques. The analyses focus on dimensionality reduction, latent variable modelling, and unsupervised clustering using **R**.

## Projects Overview

### 1. [White Wine PCA](./white-wine-pca)
**Technique:** Principal Component Analysis (PCA)
- Reduced 11 physicochemical variables into 4 interpretable dimensions (Acidity, Sulfur, Sweetness, Salts).
- Explained 64% of the total variance in the dataset.

### 2. [Behavioral Risk CCA](./behavioral-risk-cca)
**Technique:** Canonical Correlation Analysis (CCA)
- Investigated the relationship between student problem behaviours and environmental stressors.
- Identified key correlations between impulsivity/deviance and risk-taking.

### 3. [Openness Personality EFA](./openness-personality-efa)
**Technique:** Exploratory Factor Analysis (EFA)
- Uncovered 5 latent factors (e.g., Aesthetic Appreciation, Intellectual Curiosity) from a 20-item personality scale.
- Utilized Parallel Analysis and Oblique Rotation (Oblimin) for robust factor extraction.

### 4. [Cereal Nutritional Clustering](./cereal-nutritional-clustering)
**Technique:** K-Means & Hierarchical Clustering
- Segmented breakfast cereals into nutritional profiles to identify healthy options.
- Compared cluster stability across Single and Complete linkage methods.

## Tools Used
- **Language:** R
- **Libraries:** `FactoMineR`, `psych`, `CCA`, `cluster`, `tidyverse`, `ggplot2`