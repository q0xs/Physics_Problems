# Task 01 – Vector Algebra

## Problem Statement

Given two vectors in three-dimensional space,

$\vec{a} = [2, 1, -3]$

and

$\vec{b} = [4, -2, 1]$,

determine:

a) the magnitude of each vector

b) the dot product $\vec{a} \cdot \vec{b}$

c) the cross product $\vec{a} \times \vec{b}$

d) the angle between $\vec{a}$ and $\vec{b}$

## Theory

A vector in three-dimensional space can be written in component form as

$\vec{v} = [v_x, v_y, v_z]$,

where $v_x$, $v_y$, and $v_z$ are its components along the coordinate axes.

The magnitude of a vector is its length in space. For a vector $\vec{v}$, the magnitude is

$$
|\vec{v}| = \sqrt{v_x^2 + v_y^2 + v_z^2}
$$

The dot product of two vectors measures how strongly they point in the same direction. For vectors $\vec{a}$ and $\vec{b}$,

$$
\vec{a} \cdot \vec{b} = a_x b_x + a_y b_y + a_z b_z
$$

The dot product is also related to the angle $\theta$ between the vectors:

$$
\vec{a} \cdot \vec{b} = |\vec{a}| |\vec{b}| \cos\theta
$$

The cross product produces a vector perpendicular to both original vectors. In component form,

$$
\vec{a} \times \vec{b} =
\begin{pmatrix}
a_y b_z - a_z b_y \\
a_z b_x - a_x b_z \\
a_x b_y - a_y b_x
\end{pmatrix}
$$

The angle between the vectors can therefore be found from

$$
\cos\theta = \frac{\vec{a} \cdot \vec{b}}{|\vec{a}| |\vec{b}|}
$$

## Step-by-Step Solution

### Magnitude of $\vec{a}$

For

$\vec{a} = [2, 1, -3]$,

the magnitude is

$$
|\vec{a}| = \sqrt{2^2 + 1^2 + (-3)^2}
$$

Calculate each square:

$$
|\vec{a}| = \sqrt{4 + 1 + 9}
$$

$$
|\vec{a}| = \sqrt{14}
$$

Thus, the magnitude of $\vec{a}$ is

$$
|\vec{a}| = \sqrt{14}
$$

### Magnitude of $\vec{b}$

For

$\vec{b} = [4, -2, 1]$,

the magnitude is

$$
|\vec{b}| = \sqrt{4^2 + (-2)^2 + 1^2}
$$

Calculate each square:

$$
|\vec{b}| = \sqrt{16 + 4 + 1}
$$

$$
|\vec{b}| = \sqrt{21}
$$

Thus, the magnitude of $\vec{b}$ is

$$
|\vec{b}| = \sqrt{21}
$$

### Dot Product $\vec{a} \cdot \vec{b}$

Using the definition of the dot product,

$$
\vec{a} \cdot \vec{b} = 2 \cdot 4 + 1 \cdot (-2) + (-3) \cdot 1
$$

Compute each term:

$$
\vec{a} \cdot \vec{b} = 8 - 2 - 3
$$

$$
\vec{a} \cdot \vec{b} = 3
$$

### Cross Product $\vec{a} \times \vec{b}$

Substitute the vector components into the cross product formula:

$$
\vec{a} \times \vec{b} =
\begin{pmatrix}
1 \cdot 1 - (-3)(-2) \\
(-3) \cdot 4 - 2 \cdot 1 \\
2 \cdot (-2) - 1 \cdot 4
\end{pmatrix}
$$

Now simplify each component:

$$
\vec{a} \times \vec{b} =
\begin{pmatrix}
1 - 6 \\
-12 - 2 \\
-4 - 4
\end{pmatrix}
$$

$$
\vec{a} \times \vec{b} =
\begin{pmatrix}
-5 \\
-14 \\
-8
\end{pmatrix}
$$

### Angle Between the Vectors

Use the relation

$$
\cos\theta = \frac{\vec{a} \cdot \vec{b}}{|\vec{a}| |\vec{b}|}
$$

Substitute the values already found:

$$
\cos\theta = \frac{3}{\sqrt{14}\sqrt{21}}
$$

Combine the radicals:

$$
\cos\theta = \frac{3}{\sqrt{294}}
$$

Take the inverse cosine:

$$
\theta = \cos^{-1}\left(\frac{3}{\sqrt{294}}\right)
$$

For a numerical value,

$$
\theta \approx 79.9^\circ
$$

## Final Result

The magnitudes are

$$
|\vec{a}| = \sqrt{14}
$$

and

$$
|\vec{b}| = \sqrt{21}
$$

The dot product is

$$
\vec{a} \cdot \vec{b} = 3
$$

The cross product is

$$
\vec{a} \times \vec{b} =
\begin{pmatrix}
-5 \\
-14 \\
-8
\end{pmatrix}
$$

The angle between the vectors is

$$
\theta = \cos^{-1}\left(\frac{3}{\sqrt{294}}\right) \approx 79.9^\circ
$$

## Interpretation

The vector magnitudes describe the lengths of the two vectors in space. The positive dot product shows that the angle between them is less than $90^\circ$, so the vectors form an acute angle. The cross product gives a new vector perpendicular to both $\vec{a}$ and $\vec{b}$, which is important in geometry and physics when determining orientations and areas.