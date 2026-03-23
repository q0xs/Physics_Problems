# Task 08 – Work of a Variable Force and Potential Energy of a Harmonic Oscillator

## Problem Statement

Given the one-dimensional force

$$
F(x) = -kx
$$

perform the following tasks:

1. write the equation of motion and solve it,
2. calculate the work done during the displacement from $0$ to $x_0$,
3. interpret the result as potential energy,
4. verify the relation

$$
F = -\frac{dU}{dx}
$$

5. describe the graphs of $F(x)$ and $U(x)$.

## Theory

The force

$$
F(x) = -kx
$$

is the restoring force of a harmonic oscillator. The minus sign indicates that the force always points toward the equilibrium position $x=0$.

Using Newton's second law,

$$
m \frac{d^2 x}{dt^2} = -kx
$$

This is the differential equation of simple harmonic motion.

The work done by a position-dependent force between two points is

$$
W = \int_{x_1}^{x_2} F(x)\,dx
$$

A conservative force can be represented by a potential energy function $U(x)$ satisfying

$$
F(x) = -\frac{dU}{dx}
$$

## Step-by-Step Solution

### 1. Equation of motion

Start from Newton's second law:

$$
m \frac{d^2 x}{dt^2} = -kx
$$

Rearrange:

$$
\frac{d^2 x}{dt^2} + \frac{k}{m}x = 0
$$

Define the angular frequency

$$
\omega = \sqrt{\frac{k}{m}}
$$

Then the equation becomes

$$
\frac{d^2 x}{dt^2} + \omega^2 x = 0
$$

### 2. General solution

The standard solution is

$$
x(t) = A \cos(\omega t) + B \sin(\omega t)
$$

where $A$ and $B$ are constants determined by initial conditions.

An equivalent form is

$$
x(t) = C \cos(\omega t + \phi)
$$

with amplitude $C$ and phase constant $\phi$.

### 3. Work done from $0$ to $x_0$

The work is

$$
W = \int_0^{x_0} (-kx)\,dx
$$

Carry out the integration:

$$
W = -k \int_0^{x_0} x\,dx
$$

$$
W = -k \left[\frac{x^2}{2}\right]_0^{x_0}
$$

$$
W = -\frac{1}{2}k x_0^2
$$

### 4. Interpretation as potential energy

For a conservative force, the change in potential energy satisfies

$$
\Delta U = -W
$$

If the reference level is chosen so that

$$
U(0) = 0
$$

then the potential energy at position $x_0$ is

$$
U(x_0) = \frac{1}{2}k x_0^2
$$

Thus the potential energy function is

$$
U(x) = \frac{1}{2}k x^2
$$

### 5. Verification of the relation $F = -\frac{dU}{dx}$

Differentiate the potential energy:

$$
\frac{dU}{dx} = \frac{d}{dx}\left(\frac{1}{2}k x^2\right) = kx
$$

Therefore,

$$
-\frac{dU}{dx} = -kx
$$

which is exactly the given force:

$$
F(x) = -kx
$$

### 6. Graphs of $F(x)$ and $U(x)$

#### Force graph

The function

$$
F(x) = -kx
$$

is a straight line passing through the origin with negative slope $-k$.

- For $x > 0$, the force is negative.
- For $x < 0$, the force is positive.
- The force always points toward equilibrium.

#### Potential energy graph

The function

$$
U(x) = \frac{1}{2}k x^2
$$

is an upward-opening parabola with minimum at

$$
x = 0
$$

At equilibrium, the potential energy is minimum.

## Final Result

The equation of motion is

$$
m \frac{d^2 x}{dt^2} + kx = 0
$$

or equivalently

$$
\frac{d^2 x}{dt^2} + \omega^2 x = 0, \qquad \omega = \sqrt{\frac{k}{m}}
$$

Its general solution is

$$
x(t) = A \cos(\omega t) + B \sin(\omega t)
$$

The work done by the force from $0$ to $x_0$ is

$$
W = -\frac{1}{2}k x_0^2
$$

The associated potential energy is

$$
U(x) = \frac{1}{2}k x^2
$$

and it satisfies

$$
F(x) = -\frac{dU}{dx}
$$

## Interpretation

The restoring force $F(x)=-kx$ characterizes stable equilibrium. The farther the particle is displaced from equilibrium, the larger the restoring force. The quadratic potential energy means that energy increases symmetrically on both sides of the equilibrium point. This structure is the basis of simple harmonic motion.