# Task 07.01 – Uncertainty in the Volume of a Sphere

## Problem Statement

The radius of a sphere is measured as $r=(6.20\pm0.05)\text{ cm}$. Calculate the volume and its uncertainty.

## Theory

For a quantity depending on one variable, uncertainty propagation uses the derivative. The sphere volume is proportional to $r^3$, so the relative uncertainty in volume is three times the relative uncertainty in radius.

$$
V=\frac{4}{3}\pi r^3
$$

$$
\Delta V\approx\left|\frac{dV}{dr}\right|\Delta r=4\pi r^2\Delta r
$$

## Step-by-Step Solution

$$
V=\frac{4}{3}\pi(6.20)^3=998\text{ cm}^3
$$

$$
\Delta V=4\pi(6.20)^2(0.05)=24.2\text{ cm}^3
$$

## Final Result

$$
V=(998\pm24)\text{ cm}^3
$$

## Interpretation

A small radius uncertainty is amplified because volume depends on the third power of radius.
