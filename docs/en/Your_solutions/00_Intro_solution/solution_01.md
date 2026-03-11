# Physics Problem: Vector Algebra

## 1. Key Definitions and Formulas

We are given two vectors in three-dimensional space:

$$
\vec{a} = [2,\,1,\,-3], \qquad \vec{b} = [4,\,-2,\,1]
$$

Before solving the problem, let us recall the main vector operations.

### Magnitude of a vector

For a vector $\vec{v} = [v_x, v_y, v_z]$, its magnitude is:

$$
|\vec{v}| = \sqrt{v_x^2 + v_y^2 + v_z^2}
$$

### Dot product

For vectors $\vec{a} = [a_x,a_y,a_z]$ and $\vec{b} = [b_x,b_y,b_z]$, the dot product is:

$$
\vec{a}\cdot\vec{b} = a_x b_x + a_y b_y + a_z b_z
$$

### Cross product

The cross product in $\mathbb{R}^3$ is:

$$
\vec{a}\times\vec{b} =
\begin{bmatrix}
a_y b_z - a_z b_y \\
a_z b_x - a_x b_z \\
a_x b_y - a_y b_x
\end{bmatrix}
$$

### Angle between two vectors

The angle $\theta$ between two vectors satisfies:

$$
\vec{a}\cdot\vec{b} = |\vec{a}|\,|\vec{b}|\,\cos\theta
$$

Therefore,

$$
\theta = \arccos\left(\frac{\vec{a}\cdot\vec{b}}{|\vec{a}|\,|\vec{b}|}\right)
$$

## 2. Solving the Problem

We must calculate:

1. the magnitude of each vector,
2. the dot product,
3. the cross product,
4. the angle between the vectors.

## 3. Step-by-Step Derivation

### (a) Magnitude of each vector

For $\vec{a}$:

$$
|\vec{a}| = \sqrt{2^2 + 1^2 + (-3)^2}
$$

$$
|\vec{a}| = \sqrt{4 + 1 + 9} = \sqrt{14}
$$

For $\vec{b}$:

$$
|\vec{b}| = \sqrt{4^2 + (-2)^2 + 1^2}
$$

$$
|\vec{b}| = \sqrt{16 + 4 + 1} = \sqrt{21}
$$

### (b) Dot product

$$
\vec{a}\cdot\vec{b} = (2)(4) + (1)(-2) + (-3)(1)
$$

$$
\vec{a}\cdot\vec{b} = 8 - 2 - 3 = 3
$$

### (c) Cross product

Using the formula:

$$
\vec{a}\times\vec{b} =
\begin{bmatrix}
a_y b_z - a_z b_y \\
a_z b_x - a_x b_z \\
a_x b_y - a_y b_x
\end{bmatrix}
$$

First component:

$$
(1)(1) - (-3)(-2) = 1 - 6 = -5
$$

Second component:

$$
(-3)(4) - (2)(1) = -12 - 2 = -14
$$

Third component:

$$
(2)(-2) - (1)(4) = -4 - 4 = -8
$$

So,

$$
\vec{a}\times\vec{b} = [-5,\,-14,\,-8]
$$

### (d) Angle between the vectors

Use:

$$
\theta = \arccos\left(\frac{\vec{a}\cdot\vec{b}}{|\vec{a}|\,|\vec{b}|}\right)
$$

Substitute the values:

$$
\theta = \arccos\left(\frac{3}{\sqrt{14}\sqrt{21}}\right)
$$

$$
\theta = \arccos\left(\frac{3}{\sqrt{294}}\right)
$$

Numerically,

$$
\theta \approx 79.9^\circ
$$

## 4. Final Answer

$$
|\vec{a}| = \sqrt{14}, \qquad |\vec{b}| = \sqrt{21}
$$

$$
\vec{a}\cdot\vec{b} = 3
$$

$$
\vec{a}\times\vec{b} = [-5,\,-14,\,-8]
$$

$$
\theta = \arccos\left(\frac{3}{\sqrt{294}}\right)\approx 79.9^\circ
$$