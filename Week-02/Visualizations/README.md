# Visualizations — Week 2

This folder contains 6 core visualizations from Week 2 (Regression with Multiple Input Variables), generated using **Python + Matplotlib**.

| File | Description |
|------|-------------|
| `01_Multiple_Linear_Regression.png` | Shows training examples in 3D (size, bedrooms, price) with the best-fit plane, illustrating how multiple linear regression models price from several input features. |
| `02_Vectorization.png` | Compares a for-loop dot product against NumPy's vectorized `np.dot` across growing input sizes, illustrating how much faster vectorized code runs. |
| `03_Feature_Scaling.png` | Shows cost-function contours before and after z-score scaling — tall, narrow ellipses become rounder, so gradient descent heads straight for the minimum. |
| `04_Feature_Engineering.png` | Shows two raw features (frontage, depth) with a weak signal next to an engineered feature (area = frontage × depth) with a clear linear trend. |
| `05_Gradient_Descent_Multiple_Variables.png` | Shows cost vs. iteration for several learning rates (α), plus the learning curve converging to its minimum on scaled features. |
| `06_Polynomial_Regression.png` | Shows degree 1 (underfit), degree 2 (good fit) and degree 12 (overfit) curves on the same data, illustrating how polynomial features fit non-linear patterns. |

## Notes

- Each graph focuses on a single concept.
- Axes are labeled and important points (e.g., the cost minimum) are marked.
- Graphs were generated directly from code (not screenshots) and exported as PNG for easy viewing on GitHub.
