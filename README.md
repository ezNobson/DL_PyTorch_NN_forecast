# PyTorch_NN_forecast

A project for load forecasting using a neural network implemented in PyTorch.

## About

This notebook is an extension of my previous repository, where I implemented the same forecasting task in standard Python using TensorFlow.  
Here, I wanted to recreate the workflow in a Jupyter Notebook using PyTorch, to compare approaches and results between the two frameworks.

## Description

This project demonstrates an approach to time series forecasting (e.g., energy load) using a simple feedforward neural network (perceptron) built with PyTorch.  
The notebook contains the full pipeline: data preparation, normalization, model building, training, evaluation, and result visualization.

## Files

- `PyTorch_NN_forecast.ipynb` – Main Jupyter notebook with code and explanations.
- `README.md` – This file.

## Requirements

- Python 3.8+
- PyTorch
- scikit-learn
- numpy
- pandas

You can install the required libraries with:

```bash
pip install torch scikit-learn numpy pandas
```
## Pipeline Overview

- **Data loading and preprocessing**
- **Train/test split**
- **Feature and target normalization**
- **Neural network model construction and training**
- **Model evaluation (MAPE, MSE)**
- **Result visualization and comparison**

## Results

The model achieves a test MAPE of approximately 6% after normalizing the targets.

## Quick Start

1. Clone the repository or download the files.
2. Open `PyTorch_NN_forecast.ipynb` in Jupyter Notebook, JupyterLab, or PyCharm.
3. Run all cells in order.

## Author

Created by [ezNobson].

The concept of the neural network, as well as the approach to data normalization and preparation, was developed as part of a project coordinated by Professor Andrzej Bielecki and his student.

---
