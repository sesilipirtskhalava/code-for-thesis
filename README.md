# Reproducing and evaluating GEARS predictions using Systema-inspired evaluation metrics
## Contents

- `notebooks/`: Jupyter notebooks for dataset preprocessing, GEARS prediction, baseline comparison, and evaluation.

## Datasets

The datasets are not included in this repository because of file size. They were downloaded/preprocessed separately.

## Abstract

Large-scale genetic perturbation experiments, particularly Perturb-seq, have enabled systematic investigation of gene function by linking CRISPR-based perturbations to single-cell transcriptomic responses. The growing availability of perturbation datasets has led to the development of computational models that aim to predict cellular responses to previously unseen perturbations, reducing the need for exhaustive experimental screening. However, recent studies have questioned whether complex models consistently outperform simple baseline approaches and whether commonly used evaluation metrics accurately capture perturbation-specific biological effects. 
In this study we addressed the conflicting conclusions regarding the performance of perturb-seq prediction models by replicating and evaluating GEARS, a graph-based model for perturbation-response prediction, using Norman, Adamson, and Frangieh datasets. GEARS predictions were compared against simple average-based baselines and assessed using both standard performance metrics, including Pearson correlation and RMSE, as well as perturbation-centered metrics inspired by the Systema framework, including PearsonΔ and centroid accuracy. 
GEARS occasionally showed modest evidence of capturing perturbation-specific structure through centroid accuracy, particularly in the Adamson dataset. However, PearsonΔ values were generally low and did not indicate strong recovery of perturbation-specific transcriptional effects. These findings highlight the importance of benchmarking perturbation-prediction models against simple baselines and demonstrate that the interpretation of model performance depends strongly on the evaluation metric used. 
Keywords: Perturb-seq; GEARS; genetic perturbations, gene expression prediction, perturbation-response modeling. 


