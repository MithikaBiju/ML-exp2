# ML-exp2
# 📈 Linear Regression from Scratch

A clean implementation of **Simple Linear Regression** using the **California Housing Dataset**. This project demonstrates two fundamental approaches for training a linear regression model:

 **Normal Equation** (Analytical Solution)
 **Gradient Descent** (Iterative Optimization)

The notebook compares both methods and visualizes the regression line along with the cost convergence of Gradient Descent.

## 📌 Overview

This project predicts **Median House Value** based on the **Average Number of Rooms** using a simple linear regression model.

Rather than relying on Scikit-learn's built-in regression algorithm, the mathematical implementation is developed from scratch to provide a deeper understanding of how linear regression works.

##  Features

- Linear Regression implemented using the **Normal Equation**
- Linear Regression implemented using **Gradient Descent**
- Cost function calculation
- Model evaluation using:
  - Mean Squared Error (MSE)
  - R² Score
- Regression line visualization
- Cost vs. Iterations convergence plot
- Uses the California Housing Dataset

## 🛠️ Technologies Used

- Python
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## 📂 Dataset

The project uses the **California Housing Dataset** provided by Scikit-learn.

**Feature Used**
- Average Number of Rooms (`AveRooms`)

**Target Variable**
- Median House Value (`MedHouseVal`)

## 📊 Workflow

1. Load the California Housing dataset.
2. Select the input feature and target variable.
3. Add the bias term to the feature matrix.
4. Compute model parameters using the **Normal Equation**.
5. Implement **Gradient Descent** from scratch.
6. Generate predictions.
7. Evaluate model performance using MSE and R² Score.
8. Visualize the regression line and cost convergence.

## 📈 Evaluation Metrics

The model performance is measured using:

- **Mean Squared Error (MSE)**
- **R² Score (Coefficient of Determination)**

These metrics help assess the accuracy and goodness of fit of the regression model.

## 📷 Visualizations

The notebook includes:

- Scatter plot of the dataset
- Best-fit regression line
- Cost vs. Iterations graph for Gradient Descent convergence

## 📚 Learning Outcomes

This project helps in understanding:

- Fundamentals of Linear Regression
- Normal Equation
- Gradient Descent Optimization
- Cost Function Minimization
- Performance Evaluation using MSE and R² Score
- Data Visualization using Matplotlink

## 🚀 Future Improvements

- Multiple Linear Regression
- Feature Scaling
- Mini-batch Gradient Descent
- Stochastic Gradient Descent (SGD)
- Polynomial Regression
- Train/Test Split Analysis
- Additional Performance Metrics

## 📄 License

This project is created for **educational and learning purposes**. Feel free to use and modify it for academic work.

