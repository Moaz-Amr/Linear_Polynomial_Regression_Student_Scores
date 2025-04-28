# Student Score Prediction using Regression

## Short Description

This project predicts student scores based on the number of hours they studied, using data from `student_scores.csv`. It implements and compares both Simple Linear Regression and Polynomial Regression models.

## Project Overview

The notebook `Moaz.ipynb` performs the following steps:

1.  **Load Data:** Loads the student scores dataset (`student_scores.csv`).
2.  **Preprocessing:** Handles missing values in the 'Hours' column by filling them with the mean.
3.  **Linear Regression:**
    *   Trains a Simple Linear Regression model to predict 'Scores' based on 'Hours'.
    *   Calculates the Mean Squared Error (MSE).
    *   Visualizes the data points and the linear regression line.
4.  **Polynomial Regression:**
    *   Applies Polynomial Features (degree=8) to the 'Hours' data.
    *   Trains a Linear Regression model on the transformed polynomial features.
    *   Visualizes the data points and the polynomial regression curve.

## Dataset

*   **student_scores.csv:** Contains two columns: 'Hours' (number of hours studied) and 'Scores' (score obtained by the student).

## Models Used

*   **Linear Regression:** A basic regression algorithm modeling the linear relationship between hours studied and scores.
*   **Polynomial Regression:** Extends linear regression by modeling the relationship as an nth degree polynomial, potentially capturing more complex patterns.

## Requirements

*   Python 3
*   NumPy
*   Pandas
*   Scikit-learn
*   Matplotlib

## How to Run

1.  Ensure you have the required libraries installed (`pip install numpy pandas scikit-learn matplotlib`).
2.  Make sure the `student_scores.csv` file is in the same directory or provide the correct path.
3.  Run the Jupyter Notebook `Moaz.ipynb`.
