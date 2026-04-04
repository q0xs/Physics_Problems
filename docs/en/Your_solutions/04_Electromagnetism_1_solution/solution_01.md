# Task 01 – Coulomb Force at the Center of a Charged Square

## Problem Statement

Four point charges of $+1.0\,\mathrm{C}$ are placed at the corners of a square of side $1.0\,\mathrm{m}$. Determine the magnitude and direction of the electric force acting on a charge of $-2.0\,\mathrm{C}$ placed at the center of the square.

## Theory

The electrostatic force between two point charges is given by Coulomb's law:

$$
F = k \frac{|q_1 q_2|}{r^2}
$$

where

$$
k = 8.99 \times 10^9\,\mathrm{N\,m^2/C^2}
$$

For several source charges, the net force is the vector sum of the forces produced by each charge:

$$
\vec F_{\text{net}} = \sum_i \vec F_i
$$

In this problem, each corner charge is positive and the central charge is negative. Therefore, each individual force on the central charge is attractive and points from the center toward the corresponding corner.

Because the square is symmetric, opposite corner forces are equal in magnitude and opposite in direction.

## Step-by-Step Solution

### Geometry of the square

The side length is

$$
a = 1.0\,\mathrm{m}
$$

The diagonal of the square is

$$
d = a\sqrt{2}
$$

The center-to-corner distance is half the diagonal:

$$
r = \frac{d}{2} = \frac{a\sqrt{2}}{2}
$$

Thus

$$
r = \frac{\sqrt{2}}{2}\,\mathrm{m}
$$

and

$$
r^2 = \frac{1}{2}\,\mathrm{m^2}
$$

### Magnitude of the force from one corner charge

Each corner charge is

$$
q = +1.0\,\mathrm{C}
$$

The central charge is

$$
Q = -2.0\,\mathrm{C}
$$

The magnitude of the force due to one corner is

$$
F_1 = k \frac{|qQ|}{r^2}
$$

Substituting the values:

$$
F_1 = 8.99 \times 10^9 \cdot \frac{(1.0)(2.0)}{1/2}
$$

$$
F_1 = 8.99 \times 10^9 \cdot 4
$$

$$
F_1 = 3.596 \times 10^{10}\,\mathrm{N}
$$

This is the magnitude of each of the four individual forces.

### Vector cancellation

The force from the top-right corner is cancelled by the force from the bottom-left corner.

The force from the top-left corner is cancelled by the force from the bottom-right corner.

Hence the total force vector is

$$
\vec F_{\text{net}} = \vec 0
$$

## Final Result

The net electric force on the charge at the center is

$$
F_{\text{net}} = 0\,\mathrm{N}
$$

The direction is undefined because the resultant force is zero.

## Interpretation

Each corner charge exerts a strong attractive force on the central charge, but the symmetry of the square causes exact cancellation. This is a standard example of electrostatic symmetry: the field and force at a special point can vanish even though every individual contribution is nonzero.