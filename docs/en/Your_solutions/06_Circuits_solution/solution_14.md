# Task 06.14 – Series RLC Differential Equation

## Problem Statement

Write the differential equation for a series RLC circuit and compare it with a damped harmonic oscillator.

## Theory

Kirchhoff's loop rule says the source voltage equals the sum of resistor, inductor, and capacitor voltages. With $I=dq/dt$ and $V_C=q/C$, the equation becomes a second-order differential equation.

$$
L\frac{dI}{dt}+RI+V_C=V(t)
$$

$$
L\frac{d^2q}{dt^2}+R\frac{dq}{dt}+\frac{q}{C}=V(t)
$$

## Step-by-Step Solution

The damped oscillator equation is

$$
m\frac{d^2x}{dt^2}+b\frac{dx}{dt}+kx=F(t)
$$

The correspondence is $L\leftrightarrow m$, $R\leftrightarrow b$, $1/C\leftrightarrow k$, $q\leftrightarrow x$, and $V(t)\leftrightarrow F(t)$.

## Final Result

$$
Lq^{\prime\prime}+Rq^\prime+\frac{1}{C}q=V(t)
$$

## Interpretation

The inductor stores magnetic energy like mass stores kinetic energy, while the capacitor stores electric energy like a spring stores elastic energy.
