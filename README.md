# Code Repository for:
**"Application of machine learning and complex network measures to an EEG dataset from ayahuasca experiments"**  
Published in *PLOS ONE*  
[DOI: 10.1371/journal.pone.0277257](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0277257)

## Overview
This repository contains the code used in our study combining complex network analysis and machine learning techniques to investigate EEG brain activity under the influence of ayahuasca.

## Input Data
The dataset used in this study consists of EEG recordings obtained from subjects before and after ayahuasca ingestion. Connectivity matrices were derived from the EEG signals and used to compute network measures.

> 📁 The data is publicly available and is described in detail in the **Materials and Methods** section of the paper.

## Repository Structure
- `CNN-tunning-Project-ayahuasca.ipynb`: Deep learning model tuning using CNNs to classify EEG states.
- `Calculate-all-measures.ipynb`: Computes graph-based features from EEG-derived connectivity matrices.
- `Machine-learning-Final-organized.ipynb`: Final machine learning pipeline for classification tasks.
- `measures.py`: Support functions used to extract network features.

## Citation
If you use this code, please cite our paper:
Alves, Caroline L., et al. "Application of machine learning and complex network measures to an EEG dataset from ayahuasca experiments." Plos one 17.12 (2022): e0277257.
