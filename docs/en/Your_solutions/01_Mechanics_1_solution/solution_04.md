# Task 04 – Vector Calculus

## Problem Statement

The position of an object is given by

$$
\vec{r}(t) = (3t^2)\hat{i} + (5t - 8t^2)\hat{j}
$$

Find the velocity and acceleration vectors as functions of time.

## Theory

In planar motion, the velocity vector is the derivative of the position vector with respect to time:

$$
\vec v(t) = \frac{d\vec r}{dt}
$$

The acceleration vector is the derivative of the velocity vector, or equivalently the second derivative of the position vector:

$$
\vec a(t) = \frac{d\vec v}{dt} = \frac{d^2\vec r}{dt^2}
$$

Differentiation is performed componentwise.

## Step-by-Step Solution

The position vector is

$$
\vec r(t) = 3t^2 \hat i + (5t - 8t^2)\hat j
$$

### 1. Velocity vector

Differentiate each component with respect to $t$:

For the $\hat i$ component,

$$
\frac{d}{dt}(3t^2) = 6t
$$

For the $\hat j$ component,

$$
\frac{d}{dt}(5t - 8t^2) = 5 - 16t
$$

Therefore,

$$
\vec v(t) = 6t \hat i + (5 - 16t)\hat j
$$

### 2. Acceleration vector

Differentiate the velocity components:

For the $\hat i$ component,

$$
\frac{d}{dt}(6t) = 6
$$

For the $\hat j$ component,

$$
\frac{d}{dt}(5 - 16t) = -16
$$

Hence,

$$
\vec a(t) = 6\hat i - 16\hat j
$$

## Final Result

Velocity:

$$
\vec v(t) = 6t \hat i + (5 - 16t)\hat j
$$

Acceleration:

$$
\vec a(t) = 6\hat i - 16\hat j
$$

## Interpretation

The velocity changes linearly with time in both coordinate directions. The acceleration is constant, which means the motion is uniformly accelerated in the plane. The positive $\hat i$ component of acceleration increases the horizontal velocity, while the negative $\hat j$ component decreases the vertical velocity.