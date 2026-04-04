# Task 03 – Electrostatic Equilibrium on a Line

## Problem Statement

Two fixed positive charges are placed on a line:

- $q_1 = +4\,\mathrm{C}$
- $q_2 = +9\,\mathrm{C}$

The distance between them is $2\,\mathrm{m}$. Determine the equilibrium position of a third charge

$$
q_3 = +1\,\mathrm{C}
$$

placed on the line between them.

## Theory

The third charge is in equilibrium when the net force acting on it is zero.

Because the two fixed charges are both positive, the force on the third positive charge is repulsive from each source charge. Between the charges, these two forces point in opposite directions, so cancellation is possible.

If the third charge is located a distance $x$ from $q_1$, then its distance from $q_2$ is

$$
2 - x
$$

The magnitudes of the two forces must satisfy

$$
F_1 = F_2
$$

Using Coulomb's law,

$$
k \frac{|q_1 q_3|}{x^2} = k \frac{|q_2 q_3|}{(2-x)^2}
$$

The constants $k$ and $q_3$ cancel.

## Step-by-Step Solution

### Set up the equilibrium equation

Starting from

$$
\frac{q_1}{x^2} = \frac{q_2}{(2-x)^2}
$$

substitute the given values:

$$
\frac{4}{x^2} = \frac{9}{(2-x)^2}
$$

Cross-multiplication gives

$$
4(2-x)^2 = 9x^2
$$

### Expand the equation

First expand the square:

$$
(2-x)^2 = 4 - 4x + x^2
$$

Then

$$
4(4 - 4x + x^2) = 9x^2
$$

$$
16 - 16x + 4x^2 = 9x^2
$$

Bring all terms to one side:

$$
16 - 16x - 5x^2 = 0
$$

or

$$
5x^2 + 16x - 16 = 0
$$

### Solve the quadratic equation

Using the quadratic formula,

$$
x = \frac{-16 \pm \sqrt{16^2 - 4(5)(-16)}}{2 \cdot 5}
$$

$$
x = \frac{-16 \pm \sqrt{256 + 320}}{10}
$$

$$
x = \frac{-16 \pm \sqrt{576}}{10}
$$

$$
x = \frac{-16 \pm 24}{10}
$$

Thus the two mathematical solutions are

$$
x = \frac{8}{10} = 0.8\,\mathrm{m}
$$

and

$$
x = \frac{-40}{10} = -4.0\,\mathrm{m}
$$

The value $x = -4.0\,\mathrm{m}$ does not lie between the two charges, so it is not physically acceptable in the stated configuration.

## Final Result

The equilibrium position is

$$
x = 0.8\,\mathrm{m}
$$

from the $+4\,\mathrm{C}$ charge.

Equivalently, the distance from the $+9\,\mathrm{C}$ charge is

$$
2.0 - 0.8 = 1.2\,\mathrm{m}
$$

## Interpretation

The equilibrium point lies closer to the weaker charge. This is physically necessary because the weaker repulsive field must act over a shorter distance in order to balance the stronger field of the $+9\,\mathrm{C}$ charge.