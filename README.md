# Cubic Equation Solver using Gradient Descent

This Python script solves a cubic equation of the form:

\[ ax^3 + bx^2 + cx + d = 0 \]

using a simple implementation of gradient descent.

## Description

Gradient descent is an optimization technique used to find the minimum value of a function. It's analogous to finding the lowest point in a hilly terrain by taking steps in the direction of the steepest descent.

In essence, gradient descent helps us find the optimal solution to a problem by iteratively adjusting parameters to reduce the error or loss. Here's a simplified explanation of how it works:

1. **Initialization**: Start with an initial guess for the variable.
2. **Gradient Calculation**: Compute the gradient (or slope) of the function at the current point. This gradient tells us how steep the function is and in which direction it is increasing.
3. **Update Parameters**: Adjust the variable in the opposite direction of the gradient. This step reduces the function value and moves us closer to the minimum.
4. **Repeat**: Continue the process for a specified number of iterations or until changes become minimal.

The **learning rate** controls how big a step we take in each iteration. A learning rate that's too high might lead to overshooting the minimum, while a rate that's too low might slow down the convergence. By balancing the learning rate, we ensure that the algorithm converges efficiently to the minimum value.

In this script:
1. **User Input**: You input coefficients \(a\), \(b\), \(c\), and \(d\) for the cubic equation, along with the learning rate and number of iterations (epochs).
2. **Gradient Descent**: The script starts with a random value for \(x\) and iteratively adjusts it to minimize the function value, using the gradient (slope) to update \(x\).
3. **Solution**: After running the algorithm, the script provides the estimated root of the cubic equation.

## How It Works

1. **Initialize Parameters**: Randomly start with a value for \(x\).
2. **Calculate Gradient**: Compute the gradient (slope) of the cubic function at the current \(x\).
3. **Update Value**: Adjust \(x\) in the direction opposite to the gradient to minimize the function.
4. **Iterate**: Repeat the process for a specified number of epochs.
5. **Output**: Display the cubic equation and the computed root.



