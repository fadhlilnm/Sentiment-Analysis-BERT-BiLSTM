# Analysis Notebook

## Overview

This repository contains a Jupyter Notebook for analysis and experimentation.

## Requirements

Install the following Python packages:
- Data/ML: matplotlib, numpy, pandas, seaborn, sklearn, torch
- Others: random, re, transformers

## Data

The notebook references the following data files (paths may need adjustment):
- `Gojek_preprocessed.csv`
- `gojek_10k.xlsx`

## Custom Code

- **Functions:** __getitem__, __init__, __len__, evaluate, forward, normalize_word, plot_confusion_matrix, preprocess_text, seed_everything, train_epoch
- **Classes:** BertBiLSTMMultiTask, GojekDualDataset

## ML Scope

Detected tasks/components include: PyTorch deep learning, model training / evaluation

## How to Run

1. Create and activate a virtual environment.
2. Install requirements (see above).
3. Launch Jupyter and open the notebook:
   ```bash
   jupyter lab
   # or
   jupyter notebook
   ```
4. Run cells sequentially from top to bottom.

## Reproducibility Tips
- Set a random seed where applicable (NumPy/Scikit-learn/PyTorch/TensorFlow).
- Document data versions and preprocessing steps.
- Save trained artifacts (models/metrics) with timestamps.
