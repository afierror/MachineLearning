# 📈 Linear Regression Repository

## 🌟 Overview
Implementation of **Linear Regression** from scratch (using NumPy) and with scikit-learn. Includes mathematical foundations, performance comparisons, and practical examples.

## 🚀 Quick Start

### Installation
```bash
git clone https://github.com/your-username/linear-regression.git
cd linear-regression
pip install -r requirements.txt  # numpy, matplotlib, scikit-learn
```
### Basic Usage
```python
from src.linear_regression import LinearRegression

# Generate sample data
X, y = ... # Your features and target

# Train model
model = LinearRegression(learning_rate=0.01, n_iters=1000)
model.fit(X, y)

# Predict
y_pred = model.predict(X)
```
