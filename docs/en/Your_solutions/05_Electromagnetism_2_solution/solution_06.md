# Task 06 – Electromagnetic Wave Analysis

## Problem Statement

An electromagnetic wave has its electric field component described by

$$
E_y(x,t) = 100 \sin(10^7 x - \omega t) \text{ V/m}
$$

Determine:

1. The direction of propagation
2. The wavelength $\lambda$
3. The angular frequency $\omega$
4. The equation for the magnetic field component

## Theory

A plane electromagnetic wave traveling in the positive $x$-direction has the general form

$$
E(x,t) = E_0 \sin(kx - \omega t)
$$

where

- $E_0$ is the amplitude,
- $k$ is the wave number,
- $\omega$ is the angular frequency.

The wave number and wavelength are related by

$$
k = \frac{2\pi}{\lambda}
$$

Thus,

$$
\lambda = \frac{2\pi}{k}
$$

For an electromagnetic wave in vacuum,

$$
\omega = c k
$$

where

$$
c = 3.0 \times 10^8 \text{ m/s}
$$

The electric and magnetic fields are related by

$$
E_0 = c B_0
$$

so that

$$
B_0 = \frac{E_0}{c}
$$

## Step-by-Step Solution

### 1. Direction of propagation

The electric field is written as

$$
E_y(x,t) = 100 \sin(10^7 x - \omega t)
$$

This matches the standard form

$$
\sin(kx - \omega t)
$$

Therefore, the wave propagates in the positive $x$-direction.

### 2. Wavelength

From the given equation,

$$
k = 10^7 \text{ rad/m}
$$

Use

$$
\lambda = \frac{2\pi}{k}
$$

Substitute:

$$
\lambda = \frac{2\pi}{10^7}
$$

$$
\lambda \approx 6.28 \times 10^{-7} \text{ m}
$$

This can also be written as

$$
\lambda \approx 628 \text{ nm}
$$

### 3. Angular frequency

Use

$$
\omega = c k
$$

Substitute:

$$
\omega = (3.0 \times 10^8)(10^7)
$$

$$
\omega = 3.0 \times 10^{15} \text{ rad/s}
$$

### 4. Magnetic field equation

The magnetic field amplitude is

$$
B_0 = \frac{E_0}{c}
$$

Here,

$$
E_0 = 100 \text{ V/m}
$$

Thus,

$$
B_0 = \frac{100}{3.0 \times 10^8}
$$

$$
B_0 \approx 3.33 \times 10^{-7} \text{ T}
$$

Since the electric field is in the $y$-direction and the wave propagates in the positive $x$-direction, the magnetic field must point in the $z$-direction so that

$$
\vec{E} \times \vec{B}
$$

points in the positive $x$-direction.

Therefore, the magnetic field component can be written as

$$
B_z(x,t) = 3.33 \times 10^{-7} \sin(10^7 x - \omega t) \text{ T}
$$

Using the calculated value of $\omega$,

$$
B_z(x,t) = 3.33 \times 10^{-7} \sin(10^7 x - 3.0 \times 10^{15} t) \text{ T}
$$

## Final Result

Direction of propagation:

$$
\text{positive } x \text{-direction}
$$

Wavelength:

$$
\lambda \approx 6.28 \times 10^{-7} \text{ m} = 628 \text{ nm}
$$

Angular frequency:

$$
\omega = 3.0 \times 10^{15} \text{ rad/s}
$$

Magnetic field equation:

$$
B_z(x,t) = 3.33 \times 10^{-7} \sin(10^7 x - 3.0 \times 10^{15} t) \text{ T}
$$

## Interpretation

The wave travels along the positive $x$-axis. Its wavelength lies in the visible region, near red-orange light. The magnetic field oscillates in phase with the electric field and is perpendicular both to the electric field and to the direction of propagation, which is a defining property of electromagnetic waves.