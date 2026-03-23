# Task 08 – Circular Motion

## Problem Statement

Calculate the centripetal acceleration of a person standing on the Earth's equator. The Earth's radius is approximately $6378 \text{ km}$.

## Theory

A point on the Earth's equator moves in a circle due to the Earth's rotation. For uniform circular motion, the centripetal acceleration is

$$
a_c = \omega^2 r
$$

where:

- $r$ is the radius of the circular path,
- $\omega$ is the angular speed.

The angular speed for one full rotation in period $T$ is

$$
\omega = \frac{2\pi}{T}
$$

Alternatively,

$$
a_c = \frac{v^2}{r}
$$

with

$$
v = \frac{2\pi r}{T}
$$

## Step-by-Step Solution

The Earth's radius is

$$
r = 6378 \text{ km} = 6.378 \times 10^6 \text{ m}
$$

The Earth completes approximately one rotation in

$$
T = 24 \times 3600 = 86400 \text{ s}
$$

### 1. Angular speed

$$
\omega = \frac{2\pi}{T} = \frac{2\pi}{86400}
$$

$$
\omega \approx 7.272 \times 10^{-5} \text{ rad/s}
$$

### 2. Centripetal acceleration

Use

$$
a_c = \omega^2 r
$$

Substitute the values:

$$
a_c = \left(7.272 \times 10^{-5}\right)^2 \cdot 6.378 \times 10^6
$$

First square the angular speed:

$$
\omega^2 \approx 5.288 \times 10^{-9}
$$

Then multiply by the radius:

$$
a_c \approx 5.288 \times 10^{-9} \cdot 6.378 \times 10^6
$$

$$
a_c \approx 3.37 \times 10^{-2} \text{ m/s}^2
$$

Thus,

$$
a_c \approx 0.0337 \text{ m/s}^2
$$

## Final Result

The centripetal acceleration of a person standing on the Earth's equator is approximately

$$
a_c \approx 0.0337 \text{ m/s}^2
$$

## Interpretation

This acceleration is much smaller than ordinary gravitational acceleration:

$$
g \approx 9.81 \text{ m/s}^2
$$

Indeed,

$$
\frac{a_c}{g} \approx \frac{0.0337}{9.81} \approx 0.0034
$$

so the centripetal acceleration due to Earth's rotation is only about $0.34\%$ of $g$. This is why the effect is small in everyday experience, although it is physically real.