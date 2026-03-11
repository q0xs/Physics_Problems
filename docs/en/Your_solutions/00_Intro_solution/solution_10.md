# Task 10 – Infinite Series

## Problem Statement

An ant starts at the origin and moves according to the pattern:

$1$ m east, $\frac{1}{2}$ m north, $\frac{1}{3}$ m west, $\frac{1}{4}$ m south, $\frac{1}{5}$ m east, and so on.

Determine the final position of the ant.

## Theory

The motion can be separated into horizontal and vertical components.

Horizontal motion:

- east is taken as positive
- west is taken as negative

Vertical motion:

- north is taken as positive
- south is taken as negative

This creates two infinite series.

The horizontal displacement is

$$
x = 1 - \frac{1}{3} + \frac{1}{5} - \frac{1}{7} + \cdots
$$

This is the Gregory series, whose sum is

$$
1 - \frac{1}{3} + \frac{1}{5} - \frac{1}{7} + \cdots = \frac{\pi}{4}
$$

The vertical displacement is

$$
y = \frac{1}{2} - \frac{1}{4} + \frac{1}{6} - \frac{1}{8} + \cdots
$$

This can be written as

$$
y = \frac{1}{2}\left(1 - \frac{1}{2} + \frac{1}{3} - \frac{1}{4} + \cdots\right)
$$

The alternating harmonic series satisfies

$$
1 - \frac{1}{2} + \frac{1}{3} - \frac{1}{4} + \cdots = \ln 2
$$

Therefore,

$$
y = \frac{1}{2} \ln 2
$$

## Step-by-Step Solution

### Horizontal Position

Add all east-west steps with sign:

$$
x = 1 - \frac{1}{3} + \frac{1}{5} - \frac{1}{7} + \frac{1}{9} - \cdots
$$

Recognize this as the standard Gregory series:

$$
x = \frac{\pi}{4}
$$

### Vertical Position

Add all north-south steps with sign:

$$
y = \frac{1}{2} - \frac{1}{4} + \frac{1}{6} - \frac{1}{8} + \frac{1}{10} - \cdots
$$

Factor out $\frac{1}{2}$:

$$
y = \frac{1}{2}\left(1 - \frac{1}{2} + \frac{1}{3} - \frac{1}{4} + \frac{1}{5} - \cdots\right)
$$

Recognize the alternating harmonic series:

$$
y = \frac{1}{2} \ln 2
$$

### Final Coordinate

The ant starts at the origin $(0, 0)$, so its final position is the ordered pair formed by the total horizontal and vertical displacements:

$$
\left(\frac{\pi}{4}, \frac{\ln 2}{2}\right)
$$

A decimal approximation is

$$
\left(0.7854, 0.3466\right)
$$

## Final Result

The final position of the ant is

$$
\left(\frac{\pi}{4}, \frac{\ln 2}{2}\right)
$$

which is approximately

$$
\left(0.7854, 0.3466\right)
$$

## Interpretation

The ant takes infinitely many steps, but its final displacement is finite because both the horizontal and vertical series converge. The horizontal motion converges to $\frac{\pi}{4}$ and the vertical motion converges to $\frac{\ln 2}{2}$. Therefore, the ant approaches a fixed point east and north of the origin.