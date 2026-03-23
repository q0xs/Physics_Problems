# Task 03 – Speed of a Pendulum at the Bottom of the Swing

## Problem Statement

A pendulum of length $1.0\ \mathrm{m}$ is released from an initial angle of $15^\circ$.

Determine the speed of the pendulum bob at the bottom of its swing.

## Theory

The motion can be analyzed using conservation of mechanical energy.

If the pendulum is released from rest, then initially all energy is gravitational potential energy relative to the lowest point. At the bottom, that potential energy is converted into kinetic energy.

Thus,

$$
mgh = \frac{1}{2}mv^2
$$

The vertical height difference between the initial position and the lowest point is

$$
h = L - L\cos\theta = L(1 - \cos\theta)
$$

Therefore,

$$
v = \sqrt{2gL(1-\cos\theta)}
$$

## Step-by-Step Solution

### 1. Compute the vertical drop

The length is

$$
L = 1.0\ \mathrm{m}
$$

The initial angle is

$$
\theta = 15^\circ
$$

The height difference is

$$
h = L(1-\cos\theta)
$$

Substituting the values,

$$
h = 1.0 \cdot (1 - \cos 15^\circ)
$$

Using

$$
\cos 15^\circ \approx 0.9659
$$

gives

$$
h \approx 1 - 0.9659 = 0.0341\ \mathrm{m}
$$

### 2. Apply energy conservation

Using

$$
mgh = \frac{1}{2}mv^2
$$

the mass cancels, so

$$
v = \sqrt{2gh}
$$

Substitute $g = 9.81\ \mathrm{m/s^2}$ and $h = 0.0341\ \mathrm{m}$:

$$
v = \sqrt{2 \cdot 9.81 \cdot 0.0341}
$$

$$
v = \sqrt{0.668}
$$

$$
v \approx 0.817\ \mathrm{m/s}
$$

## Final Result

The speed of the pendulum bob at the bottom is

$$
v \approx 0.82\ \mathrm{m/s}
$$

## Interpretation

Because the initial angle is small, the pendulum falls through only a small vertical distance. Consequently, the speed at the bottom is modest. The result follows directly from conversion of gravitational potential energy into kinetic energy.