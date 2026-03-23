# Task 09 – Vertical Throw with Linear Drag

## Problem Statement

The equation of motion of a vertically moving particle is

$$
m\frac{dv}{dt} = -mg - kv
$$

with initial conditions

$$
v(0) = v_0, \qquad x(0) = 10
$$

Perform the following tasks:

1. solve the equation analytically,
2. determine the maximum height,
3. compare the result with the case without drag,
4. provide a numerical simulation in Python.

## Theory

The force consists of two terms:

- gravity, $-mg$,
- linear drag, $-kv$, opposing the motion.

The equation is a first-order linear differential equation for velocity. Once $v(t)$ is known, the position is obtained by integration:

$$
v(t) = \frac{dx}{dt}
$$

The maximum height occurs when

$$
v(t_{\max}) = 0
$$

## Step-by-Step Solution

### 1. Solve the velocity equation

Start from

$$
m\frac{dv}{dt} = -mg - kv
$$

Divide by $m$:

$$
\frac{dv}{dt} + \frac{k}{m}v = -g
$$

This is a linear differential equation of the form

$$
\frac{dv}{dt} + \alpha v = -g
$$

where

$$
\alpha = \frac{k}{m}
$$

The solution is

$$
v(t) = Ce^{-\alpha t} - \frac{g}{\alpha}
$$

Since

$$
\frac{g}{\alpha} = \frac{mg}{k}
$$

we can write

$$
v(t) = Ce^{-kt/m} - \frac{mg}{k}
$$

Use the initial condition $v(0)=v_0$:

$$
v_0 = C - \frac{mg}{k}
$$

Hence,

$$
C = v_0 + \frac{mg}{k}
$$

Therefore, the velocity is

$$
v(t) = \left(v_0 + \frac{mg}{k}\right)e^{-kt/m} - \frac{mg}{k}
$$

### 2. Determine the position

Since

$$
\frac{dx}{dt} = v(t)
$$

integrate:

$$
x(t) = x(0) + \int_0^t v(s)\,ds
$$

Substitute the velocity:

$$
x(t) = 10 + \int_0^t \left[\left(v_0 + \frac{mg}{k}\right)e^{-ks/m} - \frac{mg}{k}\right] ds
$$

Integrating term by term yields

$$
x(t) = 10 + \frac{m}{k}\left(v_0 + \frac{mg}{k}\right)\left(1 - e^{-kt/m}\right) - \frac{mg}{k}t
$$

This is the complete analytical expression for the position.

### 3. Time at maximum height

At maximum height the velocity is zero:

$$
0 = \left(v_0 + \frac{mg}{k}\right)e^{-kt/m} - \frac{mg}{k}
$$

Rearrange:

$$
\left(v_0 + \frac{mg}{k}\right)e^{-kt/m} = \frac{mg}{k}
$$

Thus,

$$
e^{-kt/m} = \frac{mg}{kv_0 + mg}
$$

Take the natural logarithm:

$$
-\frac{k}{m} t_{\max} = \ln\left(\frac{mg}{kv_0 + mg}\right)
$$

Therefore,

$$
t_{\max} = \frac{m}{k}\ln\left(1 + \frac{k v_0}{mg}\right)
$$

### 4. Maximum height

Substitute $t_{\max}$ into $x(t)$.

A simplified expression is obtained by using the relation from the condition $v(t_{\max})=0$:

$$
x_{\max} = 10 + \frac{m v_0}{k} - \frac{m^2 g}{k^2}\ln\left(1 + \frac{k v_0}{mg}\right)
$$

This is the maximum height above the reference origin.

### 5. Comparison with the case without drag

If $k=0$, the motion becomes standard vertical throw:

$$
m\frac{dv}{dt} = -mg
$$

Thus,

$$
v(t) = v_0 - gt
$$

and

$$
x(t) = 10 + v_0 t - \frac{1}{2}gt^2
$$

The maximum height is reached when

$$
v_0 - gt_{\max}^{(0)} = 0
$$

so

$$
t_{\max}^{(0)} = \frac{v_0}{g}
$$

The corresponding maximum height is

$$
x_{\max}^{(0)} = 10 + \frac{v_0^2}{2g}
$$

Since drag opposes upward motion, the drag case always gives:

- smaller ascent time,
- smaller maximum height,

than the ideal case without drag.

## Final Result

The analytical velocity is

$$
v(t) = \left(v_0 + \frac{mg}{k}\right)e^{-kt/m} - \frac{mg}{k}
$$

The analytical position is

$$
x(t) = 10 + \frac{m}{k}\left(v_0 + \frac{mg}{k}\right)\left(1 - e^{-kt/m}\right) - \frac{mg}{k}t
$$

The time of maximum height is

$$
t_{\max} = \frac{m}{k}\ln\left(1 + \frac{k v_0}{mg}\right)
$$

The maximum height is

$$
x_{\max} = 10 + \frac{m v_0}{k} - \frac{m^2 g}{k^2}\ln\left(1 + \frac{k v_0}{mg}\right)
$$

Without drag, the maximum height is

$$
x_{\max}^{(0)} = 10 + \frac{v_0^2}{2g}
$$

## Interpretation

Linear drag continuously removes mechanical energy from the system. The velocity no longer decreases linearly with time, but instead approaches a terminal value in downward motion. During the upward part of the trajectory, drag reduces both the ascent duration and the maximum height.

## Numerical Simulation

The following Python script compares the analytical formulas with a simple numerical integration using the Euler method.

```python
import numpy as np
import matplotlib.pyplot as plt

# Parameters
m = 1.0
k = 0.4
g = 9.81
v0 = 15.0
x0 = 10.0

# Time grid
dt = 0.001
t_end = 4.0
t = np.arange(0, t_end + dt, dt)

# Analytical solution
v_analytic = (v0 + m * g / k) * np.exp(-k * t / m) - m * g / k
x_analytic = x0 + (m / k) * (v0 + m * g / k) * (1 - np.exp(-k * t / m)) - (m * g / k) * t

# Numerical Euler method
x_num = np.zeros_like(t)
v_num = np.zeros_like(t)
x_num[0] = x0
v_num[0] = v0

for i in range(len(t) - 1):
    a = -g - (k / m) * v_num[i]
    v_num[i + 1] = v_num[i] + a * dt
    x_num[i + 1] = x_num[i] + v_num[i] * dt

# Maximum height from analytical formula
t_max = (m / k) * np.log(1 + k * v0 / (m * g))
x_max = x0 + (m * v0) / k - (m**2 * g / k**2) * np.log(1 + k * v0 / (m * g))

print("t_max =", t_max)
print("x_max =", x_max)

plt.figure()
plt.plot(t, x_analytic, label="x(t) analytical")
plt.plot(t, x_num, "--", label="x(t) Euler")
plt.xlabel("t [s]")
plt.ylabel("x [m]")
plt.legend()
plt.grid(True)
plt.show()

plt.figure()
plt.plot(t, v_analytic, label="v(t) analytical")
plt.plot(t, v_num, "--", label="v(t) Euler")
plt.xlabel("t [s]")
plt.ylabel("v [m/s]")
plt.legend()
plt.grid(True)
plt.show()