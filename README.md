# Logistic Regression Classifier Workshop

A collection of Jupyter notebooks exploring statistical classification, logistic regression, and binary cross-entropy (log-loss).

## Project Overview

This workshop introduces binary classification through practical Python examples, including predicting whether a student passes or fails based on hours studied.

The notebooks cover the mathematical foundations of logistic regression, model training, probability predictions, and classification evaluation.

## Notebooks

### `LogisticRegressionClassifier_Workshop.ipynb`

Introduces the core concepts of statistical classification:

- Linear regression review and evaluation metrics
- Logistic regression and the sigmoid function
- Binary classification and decision boundaries
- Probability thresholds
- Log-loss (binary cross-entropy)

### `PairProgrammingReport.ipynb`

Explores logistic regression in greater depth:

- Implementing logistic regression from scratch using NumPy
- Training with gradient descent
- Comparing learning rates
- Evaluating predictions using log-loss and a confusion matrix
- Comparing accuracy and log-loss
- Verifying results against scikit-learn

## Technologies

- Python
- Jupyter Notebook
- NumPy and pandas
- Matplotlib and Plotly
- scikit-learn

## Getting Started

Clone the repository and open it in VS Code or Jupyter:
```powershell
git clone https://github.com/kinghighshow/LogisticRegressionClassifierWorkshop.git
cd LogisticRegressionClassifierWorkshop
```

Create and activate a virtual environment:

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

Install the dependencies:

```powershell
python -m pip install -r requirements.txt
```

Open a notebook, select your virtual environment as the Python kernel, and run the cells in order.

## Troubleshooting

If the virtual environment doesn't appear in VS Code's kernel selector, make sure the virtual environment is activated and ipykernel is installed. Then register the kernel using the following command.

```powershell
python -m ipykernel install --user --name logistic-regression-classifier --display-name "Logistic Regression Classifier"
```
Reload the VS Code window if necessary. Open the notebook, click Select Kernel, and look for Logistic Regression Classifier.

## Purpose

This repository contains educational exercises intended to develop an understanding of logistic regression, binary classification, and the role of cross-entropy loss in training and evaluating classification models.