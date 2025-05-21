# DL Assignment 1 – CNN and Transfer Learning

This repository contains the implementation and report for a deep learning assignment focused on image classification using Convolutional Neural Networks (CNNs) and transfer learning.

## Task Description

The goal is to evaluate the effectiveness of transfer learning by training a CNN model on the Stanford Dogs dataset and evaluating it on the Cats vs Dogs dataset through multiple experiments.

Based on the [Keras CNN tutorial](https://keras.io/examples/vision/image_classification_from_scratch/), we performed four experiments:

1. **Train from scratch** on Cats vs Dogs (baseline).
2. **Transfer learning**: Freeze all layers except the output.
3. Transfer learning: Re-train the **first two convolutional layers** along with the output.
4. Transfer learning: Re-train the **last two convolutional layers** along with the output.

## Repository Structure

- `notebook.ipynb` – Implementation of all four experiments in Keras.
- `report.pdf` – Summary of results and analysis.
- `README.md` – This file.
- `.gitignore` - Ignores datasets, model checkpoints, etc.

> **Note:** Datasets are large and excluded from version control via `.gitignore`.

## Required Libraries

Please ensure the following libraries are installed in your Python environment:

- `tensorflow`
- `keras`
- `matplotlib`
- `numpy`
- `pandas`
- `scikit-learn`

## How to Run

1. Install the dependencies:

```bash
pip install tensorflow keras matplotlib numpy pandas scikit-learn
```

2. Open notebook.ipynb using Jupyter Notebook, JupyterLab, or VS Code, and run all cells sequentially to reproduce the experiments.

**Author:**

Arian Ghadirzadeh
Deep Learning Course (TDIS22) – Assignment 1
Jönköping University, School of Engineering (JTH)
April 2025
