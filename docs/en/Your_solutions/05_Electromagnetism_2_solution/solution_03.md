# Task 03 – Magnetic Field from a Current Segment

## Problem Statement

A small segment of a line wire of length $0.1 \text{ m}$ carries a current of $3 \text{ A}$. The segment is located at a distance of $0.2 \text{ m}$ from a point $P$. Calculate the magnetic field at point $P$ due to this current segment, assuming the segment is perpendicular to the line connecting it to point $P$.

## Theory

The Biot-Savart law for a small current element gives the magnetic field magnitude

$$
dB = \frac{\mu_0}{4 \pi} \frac{I \, dl \sin \theta}{r^2}
$$

where

- $dB$ is the magnetic field due to the current element,
- $\mu_0 = 4 \pi \times 10^{-7} \text{ T m/A}$,
- $I$ is the current,
- $dl$ is the length of the wire segment,
- $r$ is the distance from the segment to the point,
- $\theta$ is the angle between the current element and the position vector.

Since the segment is perpendicular to the line connecting it to point $P$, the angle is

$$
\theta = 90^\circ
$$

and therefore

$$
\sin \theta = 1
$$

## Step-by-Step Solution

Given data:

$$
I = 3 \text{ A}
$$

$$
dl = 0.1 \text{ m}
$$

$$
r = 0.2 \text{ m}
$$

Using the Biot-Savart law:

$$
dB = \frac{\mu_0}{4 \pi} \frac{I \, dl}{r^2}
$$

Substitute $\mu_0 / 4\pi = 10^{-7}$:

$$
dB = 10^{-7} \frac{(3)(0.1)}{(0.2)^2}
$$

First compute the numerator:

$$
(3)(0.1) = 0.3
$$

Then compute the denominator:

$$
(0.2)^2 = 0.04
$$

Thus

$$
dB = 10^{-7} \times \frac{0.3}{0.04}
$$

$$
dB = 10^{-7} \times 7.5
$$

$$
dB = 7.5 \times 10^{-7} \text{ T}
$$

## Final Result

$$
B = 7.5 \times 10^{-7} \text{ T}
$$

## Interpretation

This result gives the magnetic field contribution from a short current element rather than a full wire. The field is small because the segment is short and the point is relatively far away compared with the segment length. The direction is determined by the right-hand rule and is perpendicular to both the current direction and the line joining the segment to the observation point.