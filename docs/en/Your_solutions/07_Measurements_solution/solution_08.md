# Task 07.08 – Mass-Spring Timing Measurement

## Problem Statement

Create a mass-spring simulator and use ten measurements of ten oscillations to determine the mean period, standard deviation, spring constant, and uncertainty.

## Theory

For a mass on a spring, the period is related to mass and spring constant. If the mass is exact, uncertainty in $k$ comes mainly from the period uncertainty.

$$
T=2\pi\sqrt{\frac{m}{k}}
$$

$$
k=\frac{4\pi^2m}{T^2}
$$

$$
\frac{\Delta k}{k}=2\frac{\Delta T}{T}
$$

## Step-by-Step Solution

For an example data set with mean time for ten oscillations $\bar{t}_{10}=9.02\text{ s}$ and standard deviation $s_{10}=0.08\text{ s}$,

$$
T=\frac{9.02}{10}=0.902\text{ s}
$$

$$
\Delta T=\frac{0.08}{10}=0.008\text{ s}
$$

For $m=0.200\text{ kg}$,

$$
k=\frac{4\pi^2(0.200)}{(0.902)^2}=9.70\text{ N/m}
$$

$$
\Delta k=9.70\left(2\frac{0.008}{0.902}\right)=0.17\text{ N/m}
$$

## Final Result

$$
k=(9.70\pm0.17)\text{ N/m}
$$

## Interpretation

Timing many oscillations reduces relative timing uncertainty compared with timing a single oscillation.
