# Task 06 – Variable Velocity

## Problem Statement

An object's velocity is given by

$$
v(t) = t^2 + 2t - 5
$$

If the object was at position $x=4$ when $t=0$, determine:

1. the position function,
2. the position at $t=3$,
3. the acceleration at $t=3$.

## Theory

Velocity is the derivative of position:

$$
v(t) = \frac{dx}{dt}
$$

Therefore the position function is obtained by integration:

$$
x(t) = \int v(t)\, dt + C
$$

where the constant $C$ is determined from the initial condition.

Acceleration is the derivative of velocity:

$$
a(t) = \frac{dv}{dt}
$$

## Step-by-Step Solution

The velocity function is

$$
v(t) = t^2 + 2t - 5
$$

### 1. Determine the position function

Integrate the velocity:

$$
x(t) = \int (t^2 + 2t - 5)\, dt
$$

Integrate term by term:

$$
x(t) = \frac{t^3}{3} + t^2 - 5t + C
$$

Use the initial condition $x(0)=4$:

$$
4 = \frac{0^3}{3} + 0^2 - 5\cdot 0 + C
$$

$$
C = 4
$$

Thus the position function is

$$
x(t) = \frac{t^3}{3} + t^2 - 5t + 4
$$

### 2. Position at $t=3$

Substitute $t=3$:

$$
x(3) = \frac{3^3}{3} + 3^2 - 5\cdot 3 + 4
$$

$$
x(3) = \frac{27}{3} + 9 - 15 + 4
$$

$$
x(3) = 9 + 9 - 15 + 4
$$

$$
x(3) = 7
$$

### 3. Acceleration at $t=3$

Differentiate the velocity:

$$
a(t) = \frac{d}{dt}(t^2 + 2t - 5)
$$

$$
a(t) = 2t + 2
$$

Now evaluate at $t=3$:

$$
a(3) = 2\cdot 3 + 2 = 8
$$

## Final Result

The position function is

$$
x(t) = \frac{t^3}{3} + t^2 - 5t + 4
$$

The position at $t=3$ is

$$
x(3) = 7
$$

The acceleration at $t=3$ is

$$
a(3) = 8
$$

## Interpretation

The velocity is a quadratic function of time, so the acceleration is linear in time. Since $a(3)=8>0$, the object's velocity is increasing at $t=3$. The position $x(3)=7$ indicates that the object is $3$ units to the right of its initial position $x=4$ at that time.