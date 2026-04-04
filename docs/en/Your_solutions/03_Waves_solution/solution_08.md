# Task 08 – Traveling Waves and the Wave Equation

## Problem Statement

Determine which of the following functions can describe a traveling wave by checking whether they satisfy the wave equation

$$
\frac{\partial^2 y}{\partial x^2} = \frac{1}{v^2} \frac{\partial^2 y}{\partial t^2}
$$

The candidate functions are:

a) $y(x,t) = A \cos(kx^2 - \omega t)$

b) $y(x,t) = A(x-vt)^2$

c) $y(x,t) = A \log(x+vt)$

## Theory

A standard traveling wave has the form

$$
y(x,t) = f(x-vt)
$$

or

$$
y(x,t) = f(x+vt)
$$

where $f$ is any sufficiently differentiable function.

For a function of the form

$$
y(x,t) = f(\xi)
$$

with

$$
\xi = x \mp vt
$$

the derivatives are

$$
\frac{\partial y}{\partial x} = f'(\xi)
$$

and

$$
\frac{\partial y}{\partial t} = \mp v f'(\xi)
$$

Therefore,

$$
\frac{\partial^2 y}{\partial x^2} = f''(\xi)
$$

and

$$
\frac{\partial^2 y}{\partial t^2} = v^2 f''(\xi)
$$

which gives

$$
\frac{\partial^2 y}{\partial x^2} = \frac{1}{v^2} \frac{\partial^2 y}{\partial t^2}
$$

Thus, any function depending only on $x-vt$ or $x+vt$ satisfies the wave equation.

## Step-by-Step Solution

### Part a

Consider

$$
y(x,t) = A \cos(kx^2 - \omega t)
$$

The argument contains $x^2$, not a linear combination of $x$ and $t$ of the form $x \mp vt$.

To verify this explicitly, define

$$
\phi = kx^2 - \omega t
$$

Then

$$
y = A \cos \phi
$$

First derivative with respect to $x$:

$$
\frac{\partial y}{\partial x} = -A \sin \phi \cdot \frac{\partial \phi}{\partial x}
$$

$$
\frac{\partial y}{\partial x} = -A \sin \phi \cdot 2kx
$$

$$
\frac{\partial y}{\partial x} = -2Akx \sin \phi
$$

Second derivative with respect to $x$:

$$
\frac{\partial^2 y}{\partial x^2} = -2Ak \sin \phi - 2Akx \cos \phi \cdot 2kx
$$

$$
\frac{\partial^2 y}{\partial x^2} = -2Ak \sin \phi - 4Ak^2 x^2 \cos \phi
$$

Now differentiate with respect to $t$:

$$
\frac{\partial y}{\partial t} = -A \sin \phi \cdot \frac{\partial \phi}{\partial t}
$$

$$
\frac{\partial y}{\partial t} = -A \sin \phi \cdot (-\omega)
$$

$$
\frac{\partial y}{\partial t} = A \omega \sin \phi
$$

Second derivative with respect to $t$:

$$
\frac{\partial^2 y}{\partial t^2} = A \omega \cos \phi \cdot \frac{\partial \phi}{\partial t}
$$

$$
\frac{\partial^2 y}{\partial t^2} = A \omega \cos \phi \cdot (-\omega)
$$

$$
\frac{\partial^2 y}{\partial t^2} = -A \omega^2 \cos \phi
$$

The two second derivatives do not have the form required by the wave equation, because $\partial^2 y / \partial x^2$ contains both a $\sin \phi$ term and an $x^2 \cos \phi$ term.

Therefore, function a) does not satisfy the wave equation.

### Part b

Consider

$$
y(x,t) = A(x-vt)^2
$$

Define

$$
\xi = x-vt
$$

Then

$$
y = A \xi^2
$$

This is directly a function of $x-vt$, so it should satisfy the wave equation. The derivatives confirm this.

First derivative with respect to $x$:

$$
\frac{\partial y}{\partial x} = 2A \xi
$$

Second derivative with respect to $x$:

$$
\frac{\partial^2 y}{\partial x^2} = 2A
$$

First derivative with respect to $t$:

$$
\frac{\partial y}{\partial t} = 2A \xi \cdot (-v)
$$

$$
\frac{\partial y}{\partial t} = -2Av \xi
$$

Second derivative with respect to $t$:

$$
\frac{\partial^2 y}{\partial t^2} = -2Av \cdot (-v)
$$

$$
\frac{\partial^2 y}{\partial t^2} = 2Av^2
$$

Then

$$
\frac{1}{v^2} \frac{\partial^2 y}{\partial t^2} = \frac{1}{v^2} \cdot 2Av^2
$$

$$
\frac{1}{v^2} \frac{\partial^2 y}{\partial t^2} = 2A
$$

Thus,

$$
\frac{\partial^2 y}{\partial x^2} = \frac{1}{v^2} \frac{\partial^2 y}{\partial t^2}
$$

Function b) satisfies the wave equation.

### Part c

Consider

$$
y(x,t) = A \log(x+vt)
$$

Define

$$
\xi = x+vt
$$

Then

$$
y = A \log \xi
$$

This is a function of $x+vt$, so it should satisfy the wave equation. The derivatives confirm this.

First derivative with respect to $x$:

$$
\frac{\partial y}{\partial x} = A \frac{1}{\xi}
$$

Second derivative with respect to $x$:

$$
\frac{\partial^2 y}{\partial x^2} = -A \frac{1}{\xi^2}
$$

First derivative with respect to $t$:

$$
\frac{\partial y}{\partial t} = A \frac{1}{\xi} \cdot v
$$

$$
\frac{\partial y}{\partial t} = \frac{Av}{\xi}
$$

Second derivative with respect to $t$:

$$
\frac{\partial^2 y}{\partial t^2} = Av \left( - \frac{1}{\xi^2} \right) v
$$

$$
\frac{\partial^2 y}{\partial t^2} = - \frac{Av^2}{\xi^2}
$$

Therefore,

$$
\frac{1}{v^2} \frac{\partial^2 y}{\partial t^2} = \frac{1}{v^2} \left( - \frac{Av^2}{\xi^2} \right)
$$

$$
\frac{1}{v^2} \frac{\partial^2 y}{\partial t^2} = - \frac{A}{\xi^2}
$$

Hence,

$$
\frac{\partial^2 y}{\partial x^2} = \frac{1}{v^2} \frac{\partial^2 y}{\partial t^2}
$$

Function c) satisfies the wave equation.

## Final Result

- a) $y(x,t) = A \cos(kx^2 - \omega t)$ does **not** satisfy the wave equation
- b) $y(x,t) = A(x-vt)^2$ **does** satisfy the wave equation
- c) $y(x,t) = A \log(x+vt)$ **does** satisfy the wave equation

## Interpretation

A traveling wave is not restricted to sinusoidal form. Any function of $x-vt$ or $x+vt$ is a valid traveling-wave solution of the wave equation, provided the derivatives exist. Function a) fails because its spatial dependence is not linear in $x$.