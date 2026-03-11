# Task 06 – Function Analysis

## Problem Statement

Consider the function

$$
f(x) = 3x^2 - 12x + 7
$$

Identify any local maxima or minima.

## Theory

Local maxima and minima of a differentiable function occur at critical points, where the first derivative is zero or undefined.

For a smooth polynomial such as this one, the first derivative is used to find the critical point:

$$
f'(x) = 0
$$

Then the second derivative is used to classify it:

$$
f''(x) > 0 \Rightarrow \text{local minimum}
$$

$$
f''(x) < 0 \Rightarrow \text{local maximum}
$$

A quadratic function of the form $ax^2 + bx + c$ also has a vertex, which is its turning point. If $a > 0$, the parabola opens upward and the turning point is a minimum.

## Step-by-Step Solution

Start from the function

$$
f(x) = 3x^2 - 12x + 7
$$

Differentiate with respect to $x$:

$$
f'(x) = 6x - 12
$$

Set the derivative equal to zero:

$$
6x - 12 = 0
$$

Add $12$ to both sides:

$$
6x = 12
$$

Divide by $6$:

$$
x = 2
$$

This is the critical point.

Now calculate the second derivative:

$$
f''(x) = 6
$$

Since

$$
f''(x) = 6 > 0
$$

for all $x$, the graph is concave upward everywhere, so the critical point is a local minimum.

Now evaluate the function at $x = 2$:

$$
f(2) = 3(2)^2 - 12(2) + 7
$$

$$
f(2) = 3 \cdot 4 - 24 + 7
$$

$$
f(2) = 12 - 24 + 7
$$

$$
f(2) = -5
$$

## Final Result

The function has a local minimum at

$$
x = 2
$$

with function value

$$
f(2) = -5
$$

There is no local maximum.

## Interpretation

The graph of the function is a parabola opening upward because the coefficient of $x^2$ is positive. Therefore, the turning point is the lowest point on the graph. This point is both a local minimum and the absolute minimum of the function.