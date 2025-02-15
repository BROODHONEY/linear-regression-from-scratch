# Linear Regression from Scratch: OLS vs. Gradient Descent

This project demonstrates the creation of a Linear Regression model from scratch using two different approaches: **Ordinary Least Squares (OLS)** and **Gradient Descent (GD)**. It uses the **California Housing dataset** to showcase the implementation and comparison of both methods.

---

## **Objectives:**
* Understand the theory and mathematics behind Linear Regression.
* Implement Simple Linear Regression without built-in ML libraries.
* Predict median house values using the California Housing dataset.
* Compare OLS and Gradient Descent approaches to determine the most suitable method.

---

## **Dataset:**
* **California Housing Dataset** from Scikit-learn.
* Features include median income, house age, population, etc.

---

## **Ordinary Least Squares (OLS):**
* Provides a direct, closed-form solution using the Normal Equation.
* Efficient for small to medium-sized datasets but can be computationally expensive for very large datasets.

## **Gradient Descent (GD):**
* Iterative optimization method that gradually updates coefficients to minimize the cost function.
* More suitable for large datasets and online learning, though it requires careful tuning of hyperparameters like learning rate.

## **Methods Implemented:**
* **Ordinary Least Squares (OLS):** Closed-form solution using the Normal Equation.
* **Gradient Descent (GD):** Iterative approach to find optimal coefficients.

---

## **Results:**
* Both OLS and GD produce similar results on the California Housing dataset.
* OLS is faster for smaller datasets, while GD is scalable for larger datasets.

---

## **Future Improvements:**
* Add polynomial regression and regularization.
* Implement feature selection methods.

---

## **References:**
* [Linear Regression Documentation - Scikit-learn](https://scikit-learn.org/stable/modules/linear_model.html)
* [Gradient Descent Explained](https://ml-cheatsheet.readthedocs.io/en/latest/gradient_descent.html)
* [linear-regression-from-scratch - jeppbautista](https://www.kaggle.com/code/jeppbautista/linear-regression-from-scratch/notebook#notebook-container)
* [Ordinary least squares - wikiwand](https://www.wikiwand.com/en/articles/Ordinary_least_squares)
