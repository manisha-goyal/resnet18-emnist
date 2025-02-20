# ResNet-18 for EMNIST Classification

## Overview
This repository contains the implementation and evaluation of a **ResNet-18** model for classifying handwritten digits (0-9) and uppercase letters (A-Z) using the **EMNIST dataset**. The model is trained and tested on preprocessed data and evaluated using key performance metrics.

## Repository Structure
- `ResNet18.ipynb` - Jupyter Notebook containing the implementation, training, and evaluation of the model.
- `report.pdf` - Report detailing the methodology, implementation, and results.
- `images/` - Directory containing dataset visualizations, training metrics, and predictions.

## Running the Notebook
To train and evaluate the model, open and run all cells in the Jupyter Notebook. The notebook contains configurable constants that allow you to modify dataset paths, batch sizes, number of epochs, and other hyperparameters:
```sh
jupyter notebook ResNet18.ipynb
```

## Results
- **Precision**: 0.9399
- **Recall**: 0.9316
- **F1-score**: 0.9348

The final trained model achieved **93.31%** validation accuracy. See `report.tex` for detailed analysis.
