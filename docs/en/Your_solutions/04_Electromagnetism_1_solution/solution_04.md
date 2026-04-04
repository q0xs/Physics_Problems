# Task 04 – Electric and Gravitational Forces in a Hydrogen Atom

## Problem Statement

Calculate the electric force and the gravitational force between an electron and a proton in a hydrogen atom, assuming an average separation

$$
r = 5.3 \times 10^{-11}\,\mathrm{m}
$$

Then determine the ratio

$$
\frac{F_e}{F_g}
$$

## Theory

The electric force between two charges is

$$
F_e = k \frac{e^2}{r^2}
$$

The gravitational force between two masses is

$$
F_g = G \frac{m_e m_p}{r^2}
$$

The ratio is therefore

$$
\frac{F_e}{F_g} = \frac{k e^2}{G m_e m_p}
$$

The distance cancels in the ratio, which means the relative strength of these two interactions is independent of the separation.

Constants used:

$$
k = 8.99 \times 10^9\,\mathrm{N\,m^2/C^2}
$$

$$
G = 6.67 \times 10^{-11}\,\mathrm{N\,m^2/kg^2}
$$

$$
e = 1.60 \times 10^{-19}\,\mathrm{C}
$$

$$
m_e = 9.11 \times 10^{-31}\,\mathrm{kg}
$$

$$
m_p = 1.67 \times 10^{-27}\,\mathrm{kg}
$$

## Step-by-Step Solution

### Electric force

Use

$$
F_e = k \frac{e^2}{r^2}
$$

First compute the squared values:

$$
e^2 = (1.60 \times 10^{-19})^2 = 2.56 \times 10^{-38}
$$

$$
r^2 = (5.3 \times 10^{-11})^2 = 2.809 \times 10^{-21}
$$

Now substitute:

$$
F_e = 8.99 \times 10^9 \cdot \frac{2.56 \times 10^{-38}}{2.809 \times 10^{-21}}
$$

$$
F_e \approx 8.19 \times 10^{-8}\,\mathrm{N}
$$

### Gravitational force

Use

$$
F_g = G \frac{m_e m_p}{r^2}
$$

First compute the product of the masses:

$$
m_e m_p = (9.11 \times 10^{-31})(1.67 \times 10^{-27})
$$

$$
m_e m_p \approx 1.521 \times 10^{-57}
$$

Substitute:

$$
F_g = 6.67 \times 10^{-11} \cdot \frac{1.521 \times 10^{-57}}{2.809 \times 10^{-21}}
$$

$$
F_g \approx 3.61 \times 10^{-47}\,\mathrm{N}
$$

### Force ratio

Now compute

$$
\frac{F_e}{F_g} = \frac{8.19 \times 10^{-8}}{3.61 \times 10^{-47}}
$$

$$
\frac{F_e}{F_g} \approx 2.27 \times 10^{39}
$$

## Final Result

The electric force is

$$
F_e \approx 8.19 \times 10^{-8}\,\mathrm{N}
$$

The gravitational force is

$$
F_g \approx 3.61 \times 10^{-47}\,\mathrm{N}
$$

The ratio is

$$
\frac{F_e}{F_g} \approx 2.27 \times 10^{39}
$$

## Interpretation

At the atomic scale, gravity is negligible compared with electromagnetism. The electric attraction between the electron and proton is about $10^{39}$ times stronger than their gravitational attraction. This enormous difference explains why atomic structure is governed by electromagnetic forces rather than gravitational forces.