# Task 07 – Elimination of Time and Interpretation of Acceleration

## Problem Statement

The path is given in parametric form by

$$
x(t) = 2t^2, \qquad y(t) = 3t^3
$$

Required:

1. Eliminate the parameter $t$.
2. Draw the trajectory.
3. Calculate $\vec v(t)$, $|\vec v(t)|$, $\vec a(t)$, and $|\vec a(t)|$.
4. Determine whether the acceleration is constant.

## Theory

A parametric curve in the plane is described by two functions of time, $x(t)$ and $y(t)$. Eliminating the parameter gives a direct relation between $x$ and $y$.

Velocity and acceleration are obtained from the derivatives:

$$
\vec v(t) = \left(\frac{dx}{dt}, \frac{dy}{dt}\right)
$$

$$
\vec a(t) = \left(\frac{d^2x}{dt^2}, \frac{d^2y}{dt^2}\right)
$$

Their magnitudes are

$$
|\vec v(t)| = \sqrt{\left(\frac{dx}{dt}\right)^2 + \left(\frac{dy}{dt}\right)^2}
$$

$$
|\vec a(t)| = \sqrt{\left(\frac{d^2x}{dt^2}\right)^2 + \left(\frac{d^2y}{dt^2}\right)^2}
$$

## Step-by-Step Solution

### 1. Eliminate the parameter

From

$$
x = 2t^2
$$

it follows that

$$
t^2 = \frac{x}{2}
$$

Now square the equation for $y$:

$$
y = 3t^3
$$

$$
y^2 = 9t^6
$$

Since

$$
t^6 = (t^2)^3
$$

we get

$$
y^2 = 9\left(\frac{x}{2}\right)^3
$$

Therefore,

$$
y^2 = \frac{9}{8}x^3
$$

This is the Cartesian equation of the trajectory.

### 2. Trajectory

Since

$$
x = 2t^2 \geq 0
$$

the motion occurs only for $x \geq 0$.

Also, because $y=3t^3$ changes sign with $t$:

- for $t>0$, $y>0$,
- for $t<0$, $y<0$,
- for $t=0$, $y=0$.

Thus the trajectory is a semicubical parabola with cusp at the origin, symmetric with respect to the $x$-axis in the equation $y^2 = \frac{9}{8}x^3$.

### 3. Velocity vector

Differentiate the coordinate functions:

$$
\frac{dx}{dt} = \frac{d}{dt}(2t^2) = 4t
$$

$$
\frac{dy}{dt} = \frac{d}{dt}(3t^3) = 9t^2
$$

Hence

$$
\vec v(t) = (4t, 9t^2)
$$

### 4. Speed

The speed is the magnitude of the velocity vector:

$$
|\vec v(t)| = \sqrt{(4t)^2 + (9t^2)^2}
$$

$$
|\vec v(t)| = \sqrt{16t^2 + 81t^4}
$$

Factor out $t^2$:

$$
|\vec v(t)| = \sqrt{t^2(16+81t^2)}
$$

$$
|\vec v(t)| = |t|\sqrt{16+81t^2}
$$

### 5. Acceleration vector

Differentiate the velocity components:

$$
\frac{d^2x}{dt^2} = \frac{d}{dt}(4t) = 4
$$

$$
\frac{d^2y}{dt^2} = \frac{d}{dt}(9t^2) = 18t
$$

Therefore,

$$
\vec a(t) = (4, 18t)
$$

### 6. Magnitude of acceleration

The magnitude is

$$
|\vec a(t)| = \sqrt{4^2 + (18t)^2}
$$

$$
|\vec a(t)| = \sqrt{16 + 324t^2}
$$

### 7. Is the acceleration constant?

The acceleration vector is

$$
\vec a(t) = (4,18t)
$$

Its first component is constant, but its second component depends on $t$. Therefore the acceleration vector is not constant.

Also its magnitude

$$
|\vec a(t)| = \sqrt{16+324t^2}
$$

depends on time, so the acceleration magnitude is not constant either.

## Final Result

The parameter-free equation of the trajectory is

$$
y^2 = \frac{9}{8}x^3
$$

The velocity vector is

$$
\vec v(t) = (4t, 9t^2)
$$

The speed is

$$
|\vec v(t)| = |t|\sqrt{16+81t^2}
$$

The acceleration vector is

$$
\vec a(t) = (4, 18t)
$$

The magnitude of the acceleration is

$$
|\vec a(t)| = \sqrt{16+324t^2}
$$

The acceleration is not constant.

## Interpretation

The trajectory is a cusp-shaped curve beginning at the origin. The motion is not uniform because both the direction and magnitude of velocity change with time. The acceleration has a constant horizontal component and a time-dependent vertical component, which means the force producing the motion would also have to vary with time.