# Task 01 – Pendulum Period and Gravitational Dependence

## Problem Statement

A simple pendulum has a period of $4\ \mathrm{s}$ on Earth.

1. Determine its period on the Moon, where the gravitational acceleration is approximately

$$
g_{\text{Moon}} = \frac{1}{6} g_{\text{Earth}}
$$

2. Determine the required length of a simple pendulum that has a period of exactly $1\ \mathrm{s}$ on Earth.

## Theory

For a simple pendulum undergoing small oscillations, the period is

$$
T = 2\pi \sqrt{\frac{L}{g}}
$$

where:

- $T$ is the period,
- $L$ is the pendulum length,
- $g$ is the gravitational acceleration.

For a fixed pendulum length, the period depends on gravity as

$$
T \propto \frac{1}{\sqrt{g}}
$$

Thus, when gravity decreases, the period increases.

## Step-by-Step Solution

### 1. Period on the Moon

For the same pendulum length,

$$
\frac{T_{\text{Moon}}}{T_{\text{Earth}}} = \sqrt{\frac{g_{\text{Earth}}}{g_{\text{Moon}}}}
$$

Since

$$
g_{\text{Moon}} = \frac{1}{6} g_{\text{Earth}}
$$

it follows that

$$
\frac{T_{\text{Moon}}}{T_{\text{Earth}}} = \sqrt{\frac{g_{\text{Earth}}}{g_{\text{Earth}}/6}} = \sqrt{6}
$$

Therefore,

$$
T_{\text{Moon}} = 4 \sqrt{6}\ \mathrm{s}
$$

Numerically,

$$
T_{\text{Moon}} \approx 4 \cdot 2.449 = 9.80\ \mathrm{s}
$$

### 2. Length for a period of $1\ \mathrm{s}$ on Earth

Starting from

$$
T = 2\pi \sqrt{\frac{L}{g}}
$$

solve for $L$:

$$
\frac{T}{2\pi} = \sqrt{\frac{L}{g}}
$$

Squaring both sides gives

$$
\left(\frac{T}{2\pi}\right)^2 = \frac{L}{g}
$$

Hence,

$$
L = g \left(\frac{T}{2\pi}\right)^2
$$

Using $g = 9.81\ \mathrm{m/s^2}$ and $T = 1\ \mathrm{s}$,

$$
L = 9.81 \left(\frac{1}{2\pi}\right)^2
$$

$$
L = \frac{9.81}{4\pi^2}
$$

Numerically,

$$
L \approx \frac{9.81}{39.478} \approx 0.248\ \mathrm{m}
$$

## Final Result

The period on the Moon is

$$
T_{\text{Moon}} = 4\sqrt{6}\ \mathrm{s} \approx 9.80\ \mathrm{s}
$$

The length required for a $1\ \mathrm{s}$ pendulum on Earth is

$$
L \approx 0.248\ \mathrm{m}
$$

## Interpretation

The pendulum swings more slowly on the Moon because the restoring torque due to gravity is weaker. The period increases by the factor $\sqrt{6}$.

A pendulum with a period of $1\ \mathrm{s}$ on Earth is relatively short, about $25\ \mathrm{cm}$ in length.