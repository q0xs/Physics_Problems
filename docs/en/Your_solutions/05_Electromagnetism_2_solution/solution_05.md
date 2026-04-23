# Task 05 – Energy Stored in a Parallel-Plate Capacitor

## Problem Statement

We have a parallel-plate capacitor with the following parameters:

- $S = 0.02\,\mathrm{m^2}$
- $d = 5\,\mathrm{mm}$
- $U = 500\,\mathrm{V}$

Required:

1. Calculate the capacitance $C$ of the capacitor.
2. Calculate the energy $U$ stored in the capacitor.
3. Calculate the electric field intensity $E$ between the plates.
4. Calculate the force of attraction $F$ between the plates.

## Theory

For an ideal parallel-plate capacitor in air or vacuum, the capacitance is

$$
C = \varepsilon_0 \frac{S}{d}
$$

where

- $C$ is the capacitance,
- $\varepsilon_0 = 8.854 \times 10^{-12} \text{ F/m}$,
- $S$ is the plate area,
- $d$ is the separation between the plates.

The energy stored in a capacitor is

$$
W = \frac{1}{2} C U^2
$$

The electric field between the plates is

$$
E = \frac{U}{d}
$$

The attractive force between the plates can be found from the electric pressure relation:

$$
F = \frac{1}{2} \varepsilon_0 E^2 S
$$

## Step-by-Step Solution

### 1. Capacitance

Given:

$$
S = 0.02 \text{ m}^2
$$

$$
d = 5 \text{ mm} = 5 \times 10^{-3} \text{ m}
$$

Using

$$
C = \varepsilon_0 \frac{S}{d}
$$

Substitute the values:

$$
C = 8.854 \times 10^{-12} \cdot \frac{0.02}{5 \times 10^{-3}}
$$

First evaluate the ratio:

$$
\frac{0.02}{0.005} = 4
$$

Thus

$$
C = 8.854 \times 10^{-12} \times 4
$$

$$
C = 3.54 \times 10^{-11} \text{ F}
$$

### 2. Stored energy

Voltage:

$$
U = 500 \text{ V}
$$

Use

$$
W = \frac{1}{2} C U^2
$$

Substitute:

$$
W = \frac{1}{2} \cdot 3.54 \times 10^{-11} \cdot (500)^2
$$

Compute the square:

$$
(500)^2 = 250000
$$

Then

$$
W = \frac{1}{2} \cdot 3.54 \times 10^{-11} \cdot 2.5 \times 10^5
$$

$$
W = \frac{1}{2} \cdot 8.85 \times 10^{-6}
$$

$$
W \approx 4.43 \times 10^{-6} \text{ J}
$$

### 3. Electric field intensity

Use

$$
E = \frac{U}{d}
$$

Substitute:

$$
E = \frac{500}{5 \times 10^{-3}}
$$

$$
E = 1.0 \times 10^5 \text{ V/m}
$$

### 4. Force of attraction

Use

$$
F = \frac{1}{2} \varepsilon_0 E^2 S
$$

Substitute the values:

$$
F = \frac{1}{2} \cdot 8.854 \times 10^{-12} \cdot (1.0 \times 10^5)^2 \cdot 0.02
$$

Compute the square:

$$
(1.0 \times 10^5)^2 = 1.0 \times 10^{10}
$$

Thus

$$
F = \frac{1}{2} \cdot 8.854 \times 10^{-12} \cdot 1.0 \times 10^{10} \cdot 0.02
$$

$$
F = \frac{1}{2} \cdot 8.854 \times 10^{-2} \cdot 0.02
$$

$$
F = \frac{1}{2} \cdot 1.7708 \times 10^{-3}
$$

$$
F \approx 8.85 \times 10^{-4} \text{ N}
$$

## Final Result

Capacitance:

$$
C = 3.54 \times 10^{-11} \text{ F}
$$

Stored energy:

$$
W \approx 4.43 \times 10^{-6} \text{ J}
$$

Electric field intensity:

$$
E = 1.0 \times 10^5 \text{ V/m}
$$

Force of attraction:

$$
F \approx 8.85 \times 10^{-4} \text{ N}
$$

## Interpretation

The capacitance is small because the plate area is moderate and the plate separation is relatively large compared with microscopic capacitors. The stored energy is also small despite the high voltage, since the capacitance is very small. The electric field between the plates is strong, and this field produces a measurable attractive force pulling the plates together.