# Machine Learning Methods for Complex Systems

This repository contains selected coursework from AMATH 563: Inferring Structure of Complex Systems at the University of Washington. The notebook demonstrates a PCA-based classification workflow using the MNIST handwritten digit dataset.

## Contents

- `MNIST_classification.ipynb`: Applies principal component analysis for dimensionality reduction before building and evaluating a classification model.
- `requirements.txt`: Lists the Python packages used in the notebook.
- `data/`: Placeholder folder for local dataset files.

## Methods

- Principal component analysis
- Dimensionality reduction
- Classification
- Model evaluation
- Data visualization

## Tools

- Python
- NumPy
- SciPy
- Matplotlib
- scikit-learn

## Data

The full MNIST CSV files are not included in this repository because the training file is large. To run the notebook locally, place the files in the `data/` directory:

```text
data/mnist_train.csv
data/mnist_test.csv