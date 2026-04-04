# Task 09 – Damped Harmonic Oscillator: Theory and Interactive HTML Animation

## Problem Statement

For the damped harmonic oscillator

$$
m \frac{d^2 x}{dt^2} + b \frac{dx}{dt} + kx = 0
$$

prepare an interactive HTML animation with a slider for the damping parameter $b$ that shows the behavior of the system in the underdamped, critically damped, and overdamped regimes. The animation should include:

1. the general solution,
2. the classification of cases,
3. a numerical solution using RK4,
4. an investigation of the effect of $b$,
5. the graph of $x(t)$,
6. the phase portrait.

## Theory

The damped harmonic oscillator satisfies

$$
m \ddot{x} + b \dot{x} + kx = 0
$$

Dividing by $m$ gives

$$
\ddot{x} + \frac{b}{m} \dot{x} + \frac{k}{m} x = 0
$$

The characteristic equation is

$$
r^2 + \frac{b}{m} r + \frac{k}{m} = 0
$$

or equivalently

$$
mr^2 + br + k = 0
$$

Its roots are

$$
r_{1,2} = \frac{-b \pm \sqrt{b^2 - 4mk}}{2m}
$$

The behavior is determined by the discriminant

$$
\Delta = b^2 - 4mk
$$

## Step-by-Step Solution

### General Solution

#### Underdamped Case

If

$$
b^2 < 4mk
$$

the roots are complex:

$$
r = -\frac{b}{2m} \pm i \omega_d
$$

with damped angular frequency

$$
\omega_d = \sqrt{\frac{k}{m} - \frac{b^2}{4m^2}}
$$

The solution is

$$
x(t) = e^{-bt/(2m)} \left( C_1 \cos(\omega_d t) + C_2 \sin(\omega_d t) \right)
$$

This motion oscillates while its amplitude decays exponentially.

#### Critically Damped Case

If

$$
b^2 = 4mk
$$

the characteristic equation has a repeated root

$$
r = -\frac{b}{2m}
$$

and the solution is

$$
x(t) = (C_1 + C_2 t)e^{-bt/(2m)}
$$

This case returns to equilibrium as fast as possible without oscillation.

#### Overdamped Case

If

$$
b^2 > 4mk
$$

the roots are real and distinct:

$$
r_{1,2} = \frac{-b \pm \sqrt{b^2 - 4mk}}{2m}
$$

The solution is

$$
x(t) = C_1 e^{r_1 t} + C_2 e^{r_2 t}
$$

This motion does not oscillate and approaches equilibrium more slowly than the critically damped case.

### Classification of Cases

The critical damping coefficient is

$$
b_c = 2\sqrt{mk}
$$

The classification is therefore:

$$
b < b_c \quad \Rightarrow \quad \text{underdamped}
$$

$$
b = b_c \quad \Rightarrow \quad \text{critically damped}
$$

$$
b > b_c \quad \Rightarrow \quad \text{overdamped}
$$

### Numerical Formulation for RK4

Introduce the velocity

$$
v = \dot{x}
$$

Then the second-order equation becomes the first-order system

$$
\dot{x} = v
$$

$$
\dot{v} = -\frac{b}{m} v - \frac{k}{m} x
$$

The RK4 method updates the state vector

$$
\vec{y} =
\begin{pmatrix}
x \\
v
\end{pmatrix}
$$

according to

$$
\vec{y}_{n+1} = \vec{y}_n + \frac{1}{6} \left( \vec{k}_1 + 2\vec{k}_2 + 2\vec{k}_3 + \vec{k}_4 \right)
$$

with

$$
\vec{k}_1 = h \, \vec{f}(t_n, \vec{y}_n)
$$

$$
\vec{k}_2 = h \, \vec{f}\left(t_n + \frac{h}{2}, \vec{y}_n + \frac{\vec{k}_1}{2}\right)
$$

$$
\vec{k}_3 = h \, \vec{f}\left(t_n + \frac{h}{2}, \vec{y}_n + \frac{\vec{k}_2}{2}\right)
$$

$$
\vec{k}_4 = h \, \vec{f}(t_n + h, \vec{y}_n + \vec{k}_3)
$$

### Effect of the Damping Parameter $b$

The parameter $b$ controls the removal of energy from the oscillator.

- Small $b$ leads to oscillatory motion with slowly decaying amplitude.
- At $b = b_c$, the system returns to equilibrium in the shortest non-oscillatory way.
- Large $b$ suppresses oscillation and produces slow relaxation.

### Graph of $x(t)$

The displacement-time graph distinguishes the three regimes clearly.

- Underdamped motion crosses the equilibrium position repeatedly.
- Critical damping approaches equilibrium monotonically.
- Overdamping also approaches equilibrium monotonically but more slowly.

### Phase Portrait

The phase portrait plots $v$ versus $x$.

- Underdamped motion produces a spiral toward the origin.
- Critical damping approaches the origin without spiraling.
- Overdamped motion approaches the origin along a non-oscillatory path.

## Final Result

The following HTML file implements an interactive numerical simulation with:

- a slider for $b$,
- automatic case classification,
- RK4 integration,
- a graph of $x(t)$,
- a phase portrait.

## Interpretation

The damped harmonic oscillator is a standard model for mechanical, electrical, and control systems. The transition between underdamping, critical damping, and overdamping is governed by a single threshold value $b_c = 2\sqrt{mk}$, which is directly visible in both the time series and the phase portrait.
