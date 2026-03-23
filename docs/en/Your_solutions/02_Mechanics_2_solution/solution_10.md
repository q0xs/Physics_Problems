
FILE: `task_10.md`

```markdown
# Task 10 – Motion in a Force Field and Power Transfer

## Problem Statement

The motion of a particle of mass $m = 0.5\ \mathrm{kg}$ is given by

$$
x(t) = 5t^2 - t, \qquad y(t) = 2t^3, \qquad z(t) = -3t + 2
$$

Determine the time dependence of:

1. velocity,
2. momentum,
3. acceleration,
4. force,
5. power transferred by the field.

## Theory

The position vector is

$$
\vec r(t) =
\begin{pmatrix}
x(t) \\
y(t) \\
z(t)
\end{pmatrix}
$$

The kinematic quantities are obtained by differentiation:

$$
\vec v(t) = \frac{d\vec r}{dt}
$$

$$
\vec a(t) = \frac{d\vec v}{dt}
$$

Momentum is

$$
\vec p(t) = m \vec v(t)
$$

Force is

$$
\vec F(t) = m \vec a(t)
$$

The instantaneous power delivered by the force field is

$$
P(t) = \vec F(t) \cdot \vec v(t)
$$

## Step-by-Step Solution

### 1. Position vector

Write the motion in vector form:

$$
\vec r(t) =
\begin{pmatrix}
5t^2 - t \\
2t^3 \\
-3t + 2
\end{pmatrix}
$$

### 2. Velocity

Differentiate each coordinate:

$$
\vec v(t) =
\begin{pmatrix}
\frac{d}{dt}(5t^2 - t) \\
\frac{d}{dt}(2t^3) \\
\frac{d}{dt}(-3t + 2)
\end{pmatrix}
=
\begin{pmatrix}
10t - 1 \\
6t^2 \\
-3
\end{pmatrix}
$$

### 3. Momentum

Multiply the velocity by $m=0.5\ \mathrm{kg}$:

$$
\vec p(t) = 0.5
\begin{pmatrix}
10t - 1 \\
6t^2 \\
-3
\end{pmatrix}
=
\begin{pmatrix}
5t - 0.5 \\
3t^2 \\
-1.5
\end{pmatrix}
$$

### 4. Acceleration

Differentiate the velocity:

$$
\vec a(t) =
\begin{pmatrix}
\frac{d}{dt}(10t - 1) \\
\frac{d}{dt}(6t^2) \\
\frac{d}{dt}(-3)
\end{pmatrix}
=
\begin{pmatrix}
10 \\
12t \\
0
\end{pmatrix}
$$

### 5. Force

Use Newton's second law:

$$
\vec F(t) = m \vec a(t)
$$

Thus,

$$
\vec F(t) = 0.5
\begin{pmatrix}
10 \\
12t \\
0
\end{pmatrix}
=
\begin{pmatrix}
5 \\
6t \\
0
\end{pmatrix}
$$

### 6. Power transferred by the field

Compute the scalar product:

$$
P(t) = \vec F(t) \cdot \vec v(t)
$$

Substitute the expressions:

$$
P(t) =
\begin{pmatrix}
5 \\
6t \\
0
\end{pmatrix}
\cdot
\begin{pmatrix}
10t - 1 \\
6t^2 \\
-3
\end{pmatrix}
$$

Therefore,

$$
P(t) = 5(10t - 1) + (6t)(6t^2) + 0 \cdot (-3)
$$

$$
P(t) = 50t - 5 + 36t^3
$$

Reordering terms gives

$$
P(t) = 36t^3 + 50t - 5
$$

## Final Result

The velocity is

$$
\vec v(t) =
\begin{pmatrix}
10t - 1 \\
6t^2 \\
-3
\end{pmatrix}
$$

The momentum is

$$
\vec p(t) =
\begin{pmatrix}
5t - 0.5 \\
3t^2 \\
-1.5
\end{pmatrix}
$$

The acceleration is

$$
\vec a(t) =
\begin{pmatrix}
10 \\
12t \\
0
\end{pmatrix}
$$

The force is

$$
\vec F(t) =
\begin{pmatrix}
5 \\
6t \\
0
\end{pmatrix}
$$

The power is

$$
P(t) = 36t^3 + 50t - 5
$$

## Interpretation

The force field is time-dependent because the acceleration depends on time. The power is also time-dependent and measures the rate at which the field transfers energy to the particle. Positive power means the field increases the particle's kinetic energy, while negative power would correspond to energy extraction.