# MorphoPHEN: Spatial Transcriptomics and Multi-modal Learning

**Deploying Multi-modal Learning in the Analysis of Single-cell Omics to Facilitate Perturbation Modelling**  
*Master’s Thesis Project by Jiedan Xiao*

![Title of the Project](https://github.com/JiedanX/SpatialTranscriptomic/blob/main/master%20thesis%20title.jpeg?raw=true)

## Overview

This repository contains the code and workflows developed as part of my master’s thesis, which investigates the application of machine learning (ML) and deep learning (DL) techniques in spatial multi-omics. The goal of this project is to explore clustering cell states post-perturbation modelling using spatial transcriptomics data.

## Abstract

Understanding cellular and tissue heterogeneity and its impact on organ function is a fundamental challenge in life science research. Spatial transcriptomics, which integrates imaging-based technologies with high-throughput single-cell sequencing, has revolutionised our understanding of cell and tissue organisation. This project explores the feasibility of building a computational pipeline using ML and DL methods to enhance the clustering of cell states after perturbation modelling.

- **Part A**: We optimised spatial clustering by benchmarking parameters, combining scaled spatial connectivity with gene expression data. This process significantly improved clustering accuracy, closely matching ground truth data.
- **Part B**: We focused on hyperparameter tuning using the GenKI perturbation tool on a processed DBiT-seq mouse embryo dataset. The results highlight the value of perturbation modelling in spatial multi-omics to identify key regulatory genes and assess their functional impact.

The integration of ML/DL algorithms with biological insights allows us to explore gene functions and interaction networks in a spatially resolved manner, holding potential for precision medicine and AI-driven drug discovery.

## Repository Contents

This repository includes two Jupyter notebooks that detail the core analyses:

- **ST.ipynb**  
  This notebook corresponds to Part A of the thesis. It walks through the spatial transcriptomics visium data analysis, from raw data extraction to final analysis, including clustering optimisations.
  
- **MEKO_Thesis.ipynb**  
  This notebook covers Part B of the thesis. It focuses on hyperparameter tuning of the GenKI perturbation modelling tool, providing a detailed view of the parameter adjustments made on the DBiT-seq mouse embryo dataset.
