# Task 11 – Dynamics with a Time-Dependent Force

## Problem Statement

A particle of mass $m = 3\ \mathrm{kg}$ moves under the time-dependent force

$$
\vec F(t) = (15t,\ 3t-12,\ -6t^2)\ \mathrm{N}
$$

with initial conditions

$$
\vec r(0) = (5,\ 2,\ -3)\ \mathrm{m}
$$

and

$$
\vec v(0) = (2,\ 0,\ 1)\ \mathrm{m/s}
$$

Determine the time dependence of the particle's velocity and position.

## Theory

Newton's second law in vector form is

$$
\vec F = m \vec a
$$

Thus,

$$
\vec a(t) = \frac{\vec F(t)}{m}
$$

Velocity is obtained by integrating acceleration:

$$
\vec v(t) = \vec v_0 + \int_0^t \vec a(s)\,ds
$$

Position is obtained by integrating velocity:

$$
\vec r(t) = \vec r_0 + \int_0^t \vec v(s)\,ds
$$

Because the force is given componentwise, each Cartesian component can be solved independently.

## Step-by-Step Solution

### 1. Determine the acceleration

Since $m=3\ \mathrm{kg}$,

$$
\vec a(t) = \frac{1}{3}(15t,\ 3t-12,\ -6t^2)
$$

Hence,

$$
\vec a(t) = (5t,\ t-4,\ -2t^2)
$$

### 2. Determine the velocity

Integrate each component and apply the initial velocity.

#### $x$-component

$$
a_x(t) = 5t
$$

Integrating,

$$
v_x(t) = \int 5t\,dt = \frac{5}{2}t^2 + C_x
$$

Using $v_x(0)=2$ gives

$$
C_x = 2
$$

Therefore,

$$
v_x(t) = 2 + \frac{5}{2}t^2
$$

#### $y$-component

$$
a_y(t) = t - 4
$$

Integrating,

$$
v_y(t) = \int (t-4)\,dt = \frac{1}{2}t^2 - 4t + C_y
$$

Using $v_y(0)=0$ gives

$$
C_y = 0
$$

Thus,

$$
v_y(t) = \frac{1}{2}t^2 - 4t
$$

#### $z$-component

$$
a_z(t) = -2t^2
$$

Integrating,

$$
v_z(t) = \int -2t^2\,dt = -\frac{2}{3}t^3 + C_z
$$

Using $v_z(0)=1$ gives

$$
C_z = 1
$$

Hence,

$$
v_z(t) = 1 - \frac{2}{3}t^3
$$

Collecting the components,

$$
\vec v(t) =
\begin{pmatrix}
2 + \frac{5}{2}t^2 \\
\frac{1}{2}t^2 - 4t \\
1 - \frac{2}{3}t^3
\end{pmatrix}
$$

### 3. Determine the position

Integrate each velocity component and apply the initial position.

#### $x$-component

$$
v_x(t) = 2 + \frac{5}{2}t^2
$$

Integrating,

$$
x(t) = \int \left(2 + \frac{5}{2}t^2\right)dt = 2t + \frac{5}{6}t^3 + C_1
$$

Using $x(0)=5$ gives

$$
C_1 = 5
$$

Thus,

$$
x(t) = 5 + 2t + \frac{5}{6}t^3
$$

#### $y$-component

$$
v_y(t) = \frac{1}{2}t^2 - 4t
$$

Integrating,

$$
y(t) = \int \left(\frac{1}{2}t^2 - 4t\right)dt = \frac{1}{6}t^3 - 2t^2 + C_2
$$

Using $y(0)=2$ gives

$$
C_2 = 2
$$

Hence,

$$
y(t) = 2 + \frac{1}{6}t^3 - 2t^2
$$

#### $z$-component

$$
v_z(t) = 1 - \frac{2}{3}t^3
$$

Integrating,

$$
z(t) = \int \left(1 - \frac{2}{3}t^3\right)dt = t - \frac{1}{6}t^4 + C_3
$$

Using $z(0)=-3$ gives

$$
C_3 = -3
$$

Therefore,

$$
z(t) = -3 + t - \frac{1}{6}t^4
$$

So the position vector is

$$
\vec r(t) =
\begin{pmatrix}
5 + 2t + \frac{5}{6}t^3 \\
2 + \frac{1}{6}t^3 - 2t^2 \\
-3 + t - \frac{1}{6}t^4
\end{pmatrix}
$$

## Final Result

The velocity is

$$
\vec v(t) =
\begin{pmatrix}
2 + \frac{5}{2}t^2 \\
\frac{1}{2}t^2 - 4t \\
1 - \frac{2}{3}t^3
\end{pmatrix}
$$

The position is

$$
\vec r(t) =
\begin{pmatrix}
5 + 2t + \frac{5}{6}t^3 \\
2 + \frac{1}{6}t^3 - 2t^2 \\
-3 + t - \frac{1}{6}t^4
\end{pmatrix}
$$

## Interpretation

Because the force depends explicitly on time, the acceleration is not constant. Each coordinate evolves differently:

- the $x$-motion accelerates positively with time,
- the $y$-motion experiences an initially negative acceleration due to the constant term $-12$ in the force,
- the $z$-motion is increasingly driven in the negative direction by the $-6t^2$ force component.

The result illustrates how vector motion can be constructed component by component.