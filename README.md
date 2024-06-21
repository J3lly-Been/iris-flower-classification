# Iris Flower Classification Project

![Python](https://img.shields.io/badge/python-v3.10-blue)
![License](https://img.shields.io/badge/license-MIT-green)

This project demonstrates a simple machine learning task of classifying Iris flowers into three species (setosa, versicolor, virginica) using various classification algorithms. It includes data preprocessing, exploratory data analysis (EDA), model selection, hyperparameter tuning, and evaluation.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Notebook](#notebook)
- [Libraries Used](#libraries-used)
- [License](#license)

## Introduction

The Iris flower dataset is a classic dataset used in machine learning and statistics. It consists of 150 samples with 4 features (sepal length, sepal width, petal length, petal width) per sample. The goal is to predict the species of Iris flowers based on these features.

In this project, we use three different classification algorithms:
- Decision Tree
- k-Nearest Neighbors (k-NN)
- Logistic Regression

Each algorithm is tuned using GridSearchCV to find the best hyperparameters, and their performance is evaluated on a test set using accuracy metrics and classification reports.

## Dataset

The dataset used in this project is the famous Iris dataset from scikit-learn. It is loaded using `load_iris()` function, which provides the feature data and target labels necessary for training and evaluation.

## Installation

To run this project, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/J3lly-Been/iris-flower-classification.git
   ```

2. Navigate to the project directory:

   ```bash
   cd iris-flower-classification
   ```

3. Install the required libraries:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Open and run the `iris_classification.ipynb` notebook using Jupyter Notebook or JupyterLab:

   ```bash
   jupyter notebook iris_classification.ipynb
   ```

2. Follow the notebook instructions and execute each cell to see the results of each algorithm, including accuracy scores and classification reports.

## Notebook

- `iris_classification.ipynb`: Jupyter Notebook containing the entire project code, including data loading, preprocessing, model training, hyperparameter tuning, evaluation, and visualization.

## Libraries Used

- scikit-learn
- pandas
- seaborn
- matplotlib

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
