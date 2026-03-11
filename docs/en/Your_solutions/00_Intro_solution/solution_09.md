# Task 09 – Optimization Problem

## Problem Statement

A rectangle is placed under the curve

$$
y = 3 - x^2
$$

in the first quadrant.

Determine the dimensions of the rectangle with the maximum area.

## Theory

A rectangle under a curve in the first quadrant is usually described by the coordinates of its upper-right corner. If that corner lies on the curve, then its coordinates satisfy the equation of the curve.

If the upper-right corner is $(x, y)$, then for the curve

$$
y = 3 - x^2
$$

the rectangle has:

- width $x$
- height $y = 3 - x^2$

The area is therefore

$$
A(x) = x(3 - x^2)
$$

To maximize the area, differentiate $A(x)$ and solve

$$
A'(x) = 0
$$

Then use the second derivative or the physical behavior of the function to confirm that the point gives a maximum.

## Step-by-Step Solution

Let the upper-right corner of the rectangle be $(x, y)$ on the curve.

Since the point lies on

$$
y = 3 - x^2
$$

the rectangle height is

$$
y = 3 - x^2
$$

The width is

$$
x
$$

Therefore, the area of the rectangle is

$$
A(x) = x y
$$

$$
A(x) = x(3 - x^2)
$$

Expand the expression:

$$
A(x) = 3x - x^3
$$

Now differentiate with respect to $x$:

$$
A'(x) = 3 - 3x^2
$$

Set the derivative equal to zero:

$$
3 - 3x^2 = 0
$$

Divide by $3$:

$$
1 - x^2 = 0
$$

$$
x^2 = 1
$$

Thus,

$$
x = 1
$$

Since the rectangle lies in the first quadrant, only the positive value is valid.

Now find the corresponding height:

$$
y = 3 - x^2
$$

$$
y = 3 - 1^2
$$

$$
y = 2
$$

To verify that this gives a maximum, compute the second derivative:

$$
A''(x) = -6x
$$

At $x = 1$,

$$
A''(1) = -6
$$

Since this is negative, the area function is concave downward at that point, so the area is maximal there.

## Final Result

The rectangle with maximum area has

$$
\text{width} = 1
$$

and

$$
\text{height} = 2
$$

Its maximum area is

$$
A_{\max} = 1 \cdot 2 = 2
$$

## Interpretation

As the width of the rectangle increases, its height decreases because the top edge must remain under the parabola. The optimal rectangle balances these two competing effects. The maximum-area rectangle touches the curve at the point $(1, 2)$.