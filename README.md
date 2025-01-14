# Linear Regression From Scratch

This project aims to build a linear regression model using only mathematical theory and Python programming. The goal is to provide a clear understanding of the underlying principles of linear regression, including the model, objective function, and optimization techniques.

## Project Overview

In this notebook, we will:
- Explain the concept of linear regression and its applications.
- Implement the linear regression algorithm from scratch, focusing on the mathematical foundations.
- Use gradient descent as the optimization technique to minimize the error in predictions.

## Key Components

1. **Model**: The linear regression model predicts a continuous output variable based on one or more input features using the equation \( y = mx + b \), where:
   - \( y \) is the predicted output.
   - \( m \) is the weight (slope).
   - \( x \) is the input feature.
   - \( b \) is the bias (y-intercept).

2. **Objective Function**: The Mean Squared Error (MSE) is used to quantify the difference between the actual and predicted values. The goal is to minimize this error to improve the model's accuracy.

3. **Optimizer**: Gradient descent is employed to adjust the weights and bias iteratively, moving in the direction that reduces the error.

## Getting Started

### Prerequisites

- Python 3.x
- NumPy
- Matplotlib
- scikit-learn

### Installation

You can install the required libraries using pip:

   ```bash
   pip numpy matplotlib sckit-learn
   ```

### Usage

1. Clone the repository:

```bash
git clone https://github.com/tozlukozmos/linear_regression_from_scratch.git
cd linear_regression_from_scratch
```

2. Open the Jupyter Notebook:

```bash
jupyter notebook linear_regression.ipynb
```

3. Run the cells in the notebook to see the implementation of the linear regression algorithm.

## Acknowledgments

- Inspired by various online resources and tutorials on linear regression and machine learning.

1. How to implement Linear Regression from scratch with Python (https://www.youtube.com/watch?v=ltXSoduiVwY)
2. Linear Regression From Scratch in Python (Mathematical) (https://www.youtube.com/watch?v=VmbA0pi2cRQ)
3. Linear Regression (https://ml-cheatsheet.readthedocs.io/en/latest/linear_regression.html)
4. Gradient Descent (https://ml-cheatsheet.readthedocs.io/en/latest/gradient_descent.html)
