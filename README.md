# Linear Regression with Ordinary Least Squares and Gradient Descent

This project implements linear regression using two methods: Ordinary Least Squares (OLS) and Gradient Descent. The California housing dataset is used to compare the performance of both methods.

## Overview

This project aims to compare two popular methods for linear regression:

* **Ordinary Least Squares (OLS):** A closed-form solution.

* **Gradient Descent:** An iterative optimization algorithm.

We use the California housing dataset to build linear regression models with both methods and evaluate their performance.

## Dataset

The <a src = "https://www.kaggle.com/datasets/camnugent/california-housing-prices">California housing dataset</a> consists of various features such as median income, house age, and number of rooms, used to predict median house prices in California.

## Installation

### Clone the repository:

`git clone https://github.com/BROODHONEY/linear-regression-from-scratch.git`

### Install dependencies:

`pip install pandas numpy matplotlib seaborn scikit-learn jupyter`

### Project Structure

```bash
|-- data/
|-- README.md
|-- linear-regression-from-scratch.ipynb
```

## Usage

Jupyter notebooks for step-by-step implementation can be found in the notebooks/ directory.

## Methodology

Ordinary Least Squares: Minimizes the residual sum of squares between observed and predicted values.

Gradient Descent: Iteratively adjusts coefficients by taking steps proportional to the negative gradient of the cost function.

## Results

Performance Metrics: R-squared, Mean Squared Error (MSE).

## Conclusion

This project demonstrates the strengths and weaknesses of both OLS and Gradient Descent. While OLS provides a direct solution, Gradient Descent is more flexible and can handle larger datasets.

## Future Work

* Implement Ridge and Lasso regression.

* Optimize hyperparameters using Grid Search.

* Expand the dataset or use cross-validation for more robust comparisons.

## Author

Roshan Padmanabhan

## References

https://ml-cheatsheet.readthedocs.io/en/latest/gradient_descent.html

https://www.kaggle.com/code/jeppbautista/linear-regression-from-scratch/notebook#notebook-container

https://www.wikiwand.com/en/articles/Ordinary_least_squares

https://scikit-learn.org/stable/modules/linear_model.html


