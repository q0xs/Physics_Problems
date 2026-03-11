# Task 08 – Definite Integrals

## Problem Statement

Calculate the area under the curve of the function

$$
f(x) = \sin(x)
$$

from

$$
x = 0
$$

to

$$
x = \pi
$$

## Theory

The area under a curve on an interval $[a, b]$ is given by the definite integral

$$
\int_a^b f(x) \, dx
$$

If the function is nonnegative on the interval, then the value of the definite integral is equal to the geometric area between the curve and the $x$-axis.

For the sine function, $\sin(x)$ is nonnegative on the interval from $0$ to $\pi$, so the integral directly gives the area.

An antiderivative of $\sin(x)$ is

$$
\int \sin(x) \, dx = -\cos(x)
$$

## Step-by-Step Solution

The required area is

$$
\int_0^\pi \sin(x) \, dx
$$

Use the antiderivative of $\sin(x)$:

$$
\int_0^\pi \sin(x) \, dx = \left[-\cos(x)\right]_0^\pi
$$

Now evaluate at the upper and lower limits.

At the upper limit $x = \pi$,

$$
-\cos(\pi) = -(-1) = 1
$$

At the lower limit $x = 0$,

$$
-\cos(0) = -(1) = -1
$$

Subtract the lower-limit value from the upper-limit value:

$$
\int_0^\pi \sin(x) \, dx = 1 - (-1)
$$

$$
\int_0^\pi \sin(x) \, dx = 2
$$

## Final Result

The area under the curve is

$$
2
$$

## Interpretation

The graph of $\sin(x)$ forms one positive arch between $x = 0$ and $x = \pi$. Because the curve stays above the $x$-axis on this interval, the definite integral equals the full geometric area under the curve. The total area of this arch is $2$ square units.