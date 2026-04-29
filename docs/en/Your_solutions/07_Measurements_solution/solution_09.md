# Task 07.09 – Pendulum Timing Measurement

## Problem Statement

Use a pendulum simulator or real pendulum to measure ten trials of ten oscillations, then determine the mean period, standard deviation, $g$, and uncertainty.

## Theory

For small angles, the pendulum period depends on length and gravitational acceleration. If the length is exact, uncertainty in $g$ is dominated by uncertainty in the period.

$$
T=2\pi\sqrt{\frac{L}{g}}
$$

$$
g=\frac{4\pi^2L}{T^2}
$$

$$
\frac{\Delta g}{g}=2\frac{\Delta T}{T}
$$

## Step-by-Step Solution

For an example with $L=1.000\text{ m}$, mean time for ten swings $20.10\text{ s}$, and standard deviation $0.10\text{ s}$,

$$
T=2.010\text{ s}
$$

$$
\Delta T=0.010\text{ s}
$$

$$
g=\frac{4\pi^2(1.000)}{(2.010)^2}=9.77\text{ m/s}^2
$$

$$
\Delta g=9.77\left(2\frac{0.010}{2.010}\right)=0.10\text{ m/s}^2
$$

## Final Result

$$
g=(9.77\pm0.10)\text{ m/s}^2
$$

## Interpretation

The small-angle approximation and human timing uncertainty are the main experimental limitations.
