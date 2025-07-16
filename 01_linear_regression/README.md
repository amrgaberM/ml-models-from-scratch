# Linear Regression from Scratch

A complete implementation of linear regression using only NumPy, built from first principles to demonstrate understanding of the underlying mathematics and optimization techniques.

## Overview

Linear regression is a fundamental supervised learning algorithm that models the relationship between a dependent variable and independent variables by fitting a linear equation to observed data. This implementation includes both single and multiple variable regression with gradient descent optimization.

## Mathematical Foundation

The linear regression model predicts output using the hypothesis:
```
h(x) = θ₀ + θ₁x₁ + θ₂x₂ + ... + θₙxₙ
```

Where:
- `θ₀` is the bias term (intercept)
- `θᵢ` are the feature weights
- `xᵢ` are the input features

### Cost Function
We use Mean Squared Error (MSE) as the cost function:
```
J(θ) = (1/2m) Σ(h(xᵢ) - yᵢ)²
```

### Optimization
Parameters are updated using gradient descent:
```
θⱼ := θⱼ - α * ∂J(θ)/∂θⱼ
```

## Files

### `linear_regression.py`
Core implementation containing:
- `LinearRegression` class with fit/predict methods
- Gradient descent optimization
- Cost function calculation
- Support for both single and multiple features

### `test_linear_regression.py`
Unit tests covering:
- Basic functionality verification
- Edge cases and error handling
- Convergence testing
- Comparison with analytical solution

### `notebook_demo.ipynb`
Interactive demonstration including:
- Visual examples with 1D and 2D data
- Cost function visualization
- Learning curve analysis
- Comparison with scikit-learn implementation

## Usage

```python
from linear_regression import LinearRegressionScratch
import numpy as np

# Generate sample data
X = np.random.randn(100, 1)
y = 2 * X.flatten() + 1 + np.random.randn(100) * 0.1

# Create and train model
model = LinearRegressionScratch(learning_rate=0.01, iterations=1000)
model.fit(X, y)

# Make predictions
predictions = model.predict(X)
```

## Key Features

- **Pure NumPy implementation** - No external ML libraries
- **Vectorized operations** - Efficient computation using NumPy broadcasting
- **Multiple optimization methods** - Gradient descent with configurable learning rate
- **Comprehensive testing** - Unit tests for reliability
- **Educational focus** - Clear code structure for learning

## Algorithm Details

### Gradient Descent Implementation
The gradient descent algorithm updates parameters iteratively:

1. **Forward pass**: Calculate predictions using current parameters
2. **Cost calculation**: Compute MSE loss
3. **Backward pass**: Calculate gradients
4. **Parameter update**: Update weights and bias


## Extending the Implementation

This implementation can be extended to include:
- Regularization (Ridge, Lasso)
- Different optimization algorithms (Adam, RMSprop)
- Polynomial features
- Cross-validation



## Mathematical Derivation

The gradient of the cost function with respect to parameters:
```
∂J(θ)/∂θ₀ = (1/m) Σ(h(xᵢ) - yᵢ)
∂J(θ)/∂θⱼ = (1/m) Σ(h(xᵢ) - yᵢ) * xᵢⱼ
```

This leads to the vectorized update rule implemented in the code.
