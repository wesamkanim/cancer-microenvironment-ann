Cancer Microenvironment Cell Classification (PyTorch)
Overview

This project uses a PyTorch-based artificial neural network (ANN) to classify cell types in the cancer microenvironment from single-cell RNA sequencing (scRNA-seq) data. The model predicts fibroblast, T-cell, and cancer cell classes based on gene expression profiles.

Dataset

Type: scRNA-seq gene expression data

Classes: Fibroblast, T-cell, Cancer cell

Format: CSV (data.csv)

Approach

Preprocessed scRNA-seq data and encoded class labels

Trained a fully connected ANN in PyTorch

Evaluated performance on a held-out test set

Results

The model achieved 100% accuracy on the test set under the given experimental setup, indicating strong feature separability in the dataset.

Tech Stack

Python · PyTorch · pandas · NumPy · scikit-learn · Jupyter
