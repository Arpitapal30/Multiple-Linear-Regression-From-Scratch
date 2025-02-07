# Multiple-Linear-Regression-From-Scratch

​1. Steps for Implementation
Prepare the Data: Ensure data is in matrix form.
Compute OLS Estimates: Use the closed-form equation
β^ =(X^T X)^−1 X^T Y
2. Make Predictions
Y^=X β^
Evaluate the Model: Compute R² Score and Mean Squared Error (MSE).
fit(X, y): Computes 𝛽 using the Normal Equation.
predict(X): Computes 𝑌^ using 𝑋𝛽^
​r2_score(y_true, y_pred): Evaluates model accuracy using R².
mse(y_true, y_pred): Computes Mean Squared Error.

Key Takeaways
✅ Uses closed-form solution (fast for small datasets).
✅ Works well when features are not highly correlated.
✅ Avoids iterative methods like Gradient Descent.
