# Task 12 – Work and Energy for Motion Under a Constant Force

## Problem Statement

A constant force acts on a body of mass $m = 2\ \mathrm{kg}$:

$$
\vec F = (6,\ 2)\ \mathrm{N}
$$

The body starts from

$$
\vec r(0) = (0,\ 0)\ \mathrm{m}
$$

with initial velocity

$$
\vec v(0) = (1,\ -1)\ \mathrm{m/s}
$$

Determine:

1. $\vec a(t)$,
2. $\vec v(t)$,
3. $\vec r(t)$,
4. the trajectory,
5. the work done by the force at $t=3\ \mathrm{s}$,
6. the consistency with the work-energy theorem.

## Theory

For a constant force, Newton's second law gives a constant acceleration:

$$
\vec a = \frac{\vec F}{m}
$$

The velocity and position follow from integration:

$$
\vec v(t) = \vec v_0 + \vec a t
$$

$$
\vec r(t) = \vec r_0 + \vec v_0 t + \frac{1}{2}\vec a t^2
$$

The work done by a constant force over displacement $\Delta \vec r$ is

$$
W = \vec F \cdot \Delta \vec r
$$

The work-energy theorem states

$$
W = \Delta K
$$

where

$$
K = \frac{1}{2}m v^2
$$

## Step-by-Step Solution

### 1. Acceleration

Given

$$
\vec F = (6,\ 2)\ \mathrm{N}
$$

and

$$
m = 2\ \mathrm{kg}
$$

the acceleration is

$$
\vec a = \frac{\vec F}{m} = \left(\frac{6}{2},\ \frac{2}{2}\right)
$$

Thus,

$$
\vec a = (3,\ 1)\ \mathrm{m/s^2}
$$

Since the force is constant, $\vec a(t)$ is also constant:

$$
\vec a(t) = (3,\ 1)\ \mathrm{m/s^2}
$$

### 2. Velocity

Use

$$
\vec v(t) = \vec v_0 + \vec a t
$$

with

$$
\vec v_0 = (1,\ -1)
$$

Hence,

$$
\vec v(t) = (1,\ -1) + (3,\ 1)t
$$

Therefore,

$$
\vec v(t) = (1+3t,\ -1+t)\ \mathrm{m/s}
$$

### 3. Position

Use

$$
\vec r(t) = \vec r_0 + \vec v_0 t + \frac{1}{2}\vec a t^2
$$

Since $\vec r_0=(0,0)$,

$$
\vec r(t) = (1,\ -1)t + \frac{1}{2}(3,\ 1)t^2
$$

Thus,

$$
\vec r(t) = \left(t + \frac{3}{2}t^2,\ -t + \frac{1}{2}t^2\right)
$$

So,

$$
x(t) = t + \frac{3}{2}t^2
$$

and

$$
y(t) = -t + \frac{1}{2}t^2
$$

### 4. Trajectory

The motion is most naturally represented parametrically:

$$
x(t) = t + \frac{3}{2}t^2
$$

$$
y(t) = -t + \frac{1}{2}t^2
$$

This is a parabola in the plane because both coordinates are quadratic functions of time.

A sketch of the trajectory can be drawn from the parametric equations. The particle initially moves in the direction $(1,-1)$, but the constant acceleration $(3,1)$ bends the path toward increasing $x$ and increasing $y$.

### 5. Work done by the force at $t=3\ \mathrm{s}$

First compute the position at $t=3$:

$$
x(3) = 3 + \frac{3}{2}\cdot 9 = 3 + 13.5 = 16.5
$$

$$
y(3) = -3 + \frac{1}{2}\cdot 9 = -3 + 4.5 = 1.5
$$

So the displacement from the origin is

$$
\Delta \vec r = (16.5,\ 1.5)\ \mathrm{m}
$$

The work done is

$$
W = \vec F \cdot \Delta \vec r
$$

$$
W = (6,\ 2)\cdot(16.5,\ 1.5)
$$

$$
W = 6 \cdot 16.5 + 2 \cdot 1.5
$$

$$
W = 99 + 3 = 102\ \mathrm{J}
$$

### 6. Check the work-energy theorem

#### Initial kinetic energy

At $t=0$,

$$
\vec v(0) = (1,\ -1)
$$

Therefore,

$$
v_0^2 = 1^2 + (-1)^2 = 2
$$

So,

$$
K_0 = \frac{1}{2} \cdot 2 \cdot 2 = 2\ \mathrm{J}
$$

#### Final kinetic energy at $t=3\ \mathrm{s}$

The velocity at $t=3$ is

$$
\vec v(3) = (1+3\cdot 3,\ -1+3) = (10,\ 2)
$$

Then

$$
v(3)^2 = 10^2 + 2^2 = 104
$$

Hence,

$$
K_3 = \frac{1}{2} \cdot 2 \cdot 104 = 104\ \mathrm{J}
$$

The kinetic energy change is

$$
\Delta K = K_3 - K_0 = 104 - 2 = 102\ \mathrm{J}
$$

Thus,

$$
W = \Delta K = 102\ \mathrm{J}
$$

which confirms the work-energy theorem.

## Final Result

The acceleration is

$$
\vec a(t) = (3,\ 1)\ \mathrm{m/s^2}
$$

The velocity is

$$
\vec v(t) = (1+3t,\ -1+t)\ \mathrm{m/s}
$$

The position is

$$
\vec r(t) = \left(t + \frac{3}{2}t^2,\ -t + \frac{1}{2}t^2\right)\ \mathrm{m}
$$

The trajectory is a parabola described parametrically by the above equations.

The work done by the force up to $t=3\ \mathrm{s}$ is

$$
W = 102\ \mathrm{J}
$$

The work-energy theorem is verified because

$$
\Delta K = 102\ \mathrm{J}
$$

## Interpretation

A constant force produces constant acceleration, so the motion is uniformly accelerated in both coordinates. The work done by the force appears exactly as an increase in kinetic energy, which is the content of the work-energy theorem.