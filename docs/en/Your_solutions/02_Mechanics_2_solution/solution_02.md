# Task 02 – Harmonic Motion of a Mass-Spring System

## Problem Statement

A mass of $10\ \mathrm{kg}$ is attached to a spring and oscillates according to

$$
x(t) = 0.2 \cos(10\pi t)
$$

where $x$ is measured in meters.

Determine:

1. the spring constant $k$,
2. the total mechanical energy of the system.

## Theory

For a simple harmonic oscillator,

$$
x(t) = A \cos(\omega t + \phi)
$$

where:

- $A$ is the amplitude,
- $\omega$ is the angular frequency,
- $\phi$ is the phase constant.

For a spring-mass system,

$$
\omega = \sqrt{\frac{k}{m}}
$$

Thus,

$$
k = m \omega^2
$$

The total mechanical energy of the oscillator is constant and equals

$$
E = \frac{1}{2} k A^2
$$

It can also be written as

$$
E = \frac{1}{2} m \omega^2 A^2
$$

## Step-by-Step Solution

### 1. Read the amplitude and angular frequency

The given equation is

$$
x(t) = 0.2 \cos(10\pi t)
$$

Comparing with the standard form,

$$
x(t) = A \cos(\omega t + \phi)
$$

gives

$$
A = 0.2\ \mathrm{m}
$$

and

$$
\omega = 10\pi\ \mathrm{rad/s}
$$

### 2. Determine the spring constant

Using

$$
k = m \omega^2
$$

with $m = 10\ \mathrm{kg}$ and $\omega = 10\pi$,

$$
k = 10 (10\pi)^2
$$

$$
k = 10 \cdot 100\pi^2
$$

$$
k = 1000\pi^2\ \mathrm{N/m}
$$

Numerically,

$$
k \approx 1000 \cdot 9.8696 = 9869.6\ \mathrm{N/m}
$$

### 3. Determine the total mechanical energy

The total energy is

$$
E = \frac{1}{2} k A^2
$$

Substituting $k = 1000\pi^2$ and $A = 0.2$,

$$
E = \frac{1}{2} \cdot 1000\pi^2 \cdot (0.2)^2
$$

Since

$$
(0.2)^2 = 0.04
$$

we obtain

$$
E = \frac{1}{2} \cdot 1000\pi^2 \cdot 0.04
$$

$$
E = 20\pi^2\ \mathrm{J}
$$

Numerically,

$$
E \approx 20 \cdot 9.8696 = 197.4\ \mathrm{J}
$$

## Final Result

The spring constant is

$$
k = 1000\pi^2\ \mathrm{N/m} \approx 9.87 \times 10^3\ \mathrm{N/m}
$$

The total mechanical energy is

$$
E = 20\pi^2\ \mathrm{J} \approx 197.4\ \mathrm{J}
$$

## Interpretation

The large value of $k$ indicates a stiff spring. The energy remains constant because the motion is ideal simple harmonic motion with no damping. Energy continuously exchanges between spring potential energy and kinetic energy.