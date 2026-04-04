# Task 09 – Magnetic Force from a Vector Cross Product

## Problem Statement

A proton moves with velocity

$$
\vec v = (2\hat i - 4\hat j + \hat k)\,\mathrm{m/s}
$$

in a region where the magnetic field is

$$
\vec B = (\hat i + 2\hat j - \hat k)\,\mathrm{T}
$$

Determine the magnitude of the magnetic force experienced by the proton.

## Theory

The magnetic force acting on a moving charge is

$$
\vec F = q \,\vec v \times \vec B
$$

For a proton,

$$
q = e = 1.60 \times 10^{-19}\,\mathrm{C}
$$

The magnitude is

$$
|\vec F| = q |\vec v \times \vec B|
$$

Thus the problem reduces to computing the cross product and then taking its magnitude.

## Step-by-Step Solution

### Component form of the vectors

Write the two vectors as

$$
\vec v = (2,-4,1)
$$

$$
\vec B = (1,2,-1)
$$

### Cross product

Using the determinant form,

$$
\vec v \times \vec B =
\begin{vmatrix}
\hat i & \hat j & \hat k \\
2 & -4 & 1 \\
1 & 2 & -1
\end{vmatrix}
$$

Expanding along the first row:

$$
\vec v \times \vec B =
\hat i
\begin{vmatrix}
-4 & 1 \\
2 & -1
\end{vmatrix}
-
\hat j
\begin{vmatrix}
2 & 1 \\
1 & -1
\end{vmatrix}
+
\hat k
\begin{vmatrix}
2 & -4 \\
1 & 2
\end{vmatrix}
$$

Now evaluate each minor.

For the $\hat i$ component:

$$
(-4)(-1) - (1)(2) = 4 - 2 = 2
$$

For the $\hat j$ component:

$$
(2)(-1) - (1)(1) = -2 - 1 = -3
$$

Because of the minus sign in front of the $\hat j$ term, this contributes

$$
-(-3)\hat j = 3\hat j
$$

For the $\hat k$ component:

$$
(2)(2) - (-4)(1) = 4 + 4 = 8
$$

Hence,

$$
\vec v \times \vec B = 2\hat i + 3\hat j + 8\hat k
$$

### Magnitude of the cross product

Compute the magnitude:

$$
|\vec v \times \vec B| = \sqrt{2^2 + 3^2 + 8^2}
$$

$$
|\vec v \times \vec B| = \sqrt{4 + 9 + 64}
$$

$$
|\vec v \times \vec B| = \sqrt{77}
$$

$$
|\vec v \times \vec B| \approx 8.775
$$

### Magnetic force magnitude

Now multiply by the proton charge:

$$
|\vec F| = q |\vec v \times \vec B|
$$

$$
|\vec F| = (1.60 \times 10^{-19})(8.775)
$$

$$
|\vec F| \approx 1.40 \times 10^{-18}\,\mathrm{N}
$$

## Final Result

The magnitude of the magnetic force is

$$
|\vec F| \approx 1.40 \times 10^{-18}\,\mathrm{N}
$$

## Interpretation

The cross product isolates the component of velocity perpendicular to the magnetic field. The result shows that even for modest vector components, the force direction is fully three-dimensional and is determined by vector geometry rather than by scalar multiplication.