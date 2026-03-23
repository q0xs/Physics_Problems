# Task 01 – Projectile Motion

## Problem Statement

A projectile is fired from the ground with initial speed $v_0 = 100 \text{ m/s}$ at an angle $\theta = 37^\circ$ above the horizontal. Air resistance is neglected.

Required:

1. Derive the differential equations of motion in the horizontal and vertical directions.
2. Determine the time of flight.
3. Determine the maximum height.
4. Determine the range.

## Theory

Projectile motion without air resistance is governed only by gravity. The only force acting on the projectile after launch is its weight,

$$
\vec F = m \vec g
$$

with

$$
\vec g = (0, -g)
$$

where $g \approx 9.81 \text{ m/s}^2$.

By Newton's second law,

$$
m \vec a = \vec F
$$

so the acceleration is constant:

$$
\vec a = (0, -g)
$$

The initial velocity is decomposed into horizontal and vertical components:

$$
v_{0x} = v_0 \cos \theta
$$

$$
v_{0y} = v_0 \sin \theta
$$

For motion starting from the ground, the initial position is taken as

$$
x(0) = 0, \qquad y(0) = 0
$$

## Step-by-Step Solution

### 1. Differential equations of motion

Since the acceleration components are

$$
a_x = 0, \qquad a_y = -g
$$

the equations of motion are

$$
\frac{d^2 x}{dt^2} = 0
$$

$$
\frac{d^2 y}{dt^2} = -g
$$

Integrating the horizontal equation once gives

$$
\frac{dx}{dt} = v_x(t) = v_{0x} = v_0 \cos \theta
$$

Integrating again,

$$
x(t) = v_0 \cos \theta \, t
$$

because $x(0)=0$.

For the vertical motion,

$$
\frac{dy}{dt} = v_y(t) = v_0 \sin \theta - gt
$$

and after integrating,

$$
y(t) = v_0 \sin \theta \, t - \frac{1}{2}gt^2
$$

because $y(0)=0$.

Thus the parametric equations of motion are

$$
x(t) = v_0 \cos \theta \, t
$$

$$
y(t) = v_0 \sin \theta \, t - \frac{1}{2}gt^2
$$

For the numerical values,

$$
v_{0x} = 100 \cos 37^\circ
$$

$$
v_{0y} = 100 \sin 37^\circ
$$

Using

$$
\cos 37^\circ \approx 0.7986, \qquad \sin 37^\circ \approx 0.6018
$$

one gets

$$
v_{0x} \approx 79.86 \text{ m/s}
$$

$$
v_{0y} \approx 60.18 \text{ m/s}
$$

Hence

$$
x(t) \approx 79.86\, t
$$

$$
y(t) \approx 60.18\, t - 4.905\, t^2
$$

### 2. Time of flight

The time of flight is the time when the projectile returns to the ground, that is when $y(t)=0$ with $t>0$.

Set

$$
v_0 \sin \theta \, t - \frac{1}{2}gt^2 = 0
$$

Factor out $t$:

$$
t \left( v_0 \sin \theta - \frac{1}{2}gt \right) = 0
$$

The solutions are

$$
t = 0
$$

and

$$
t = \frac{2 v_0 \sin \theta}{g}
$$

Therefore the time of flight is

$$
T = \frac{2 v_0 \sin \theta}{g}
$$

Substituting the values,

$$
T = \frac{2 \cdot 100 \cdot \sin 37^\circ}{9.81}
$$

$$
T \approx \frac{200 \cdot 0.6018}{9.81}
$$

$$
T \approx \frac{120.36}{9.81}
$$

$$
T \approx 12.27 \text{ s}
$$

### 3. Maximum height

The maximum height occurs when the vertical velocity becomes zero:

$$
v_y(t) = v_0 \sin \theta - gt = 0
$$

Thus the time to reach the top is

$$
t_{\text{top}} = \frac{v_0 \sin \theta}{g}
$$

Substituting,

$$
t_{\text{top}} = \frac{100 \sin 37^\circ}{9.81}
$$

$$
t_{\text{top}} \approx \frac{60.18}{9.81}
$$

$$
t_{\text{top}} \approx 6.14 \text{ s}
$$

Now evaluate $y(t)$ at this time:

$$
H_{\max} = v_0 \sin \theta \, t_{\text{top}} - \frac{1}{2}g t_{\text{top}}^2
$$

A standard equivalent formula is

$$
H_{\max} = \frac{(v_0 \sin \theta)^2}{2g}
$$

Substituting,

$$
H_{\max} = \frac{(100 \sin 37^\circ)^2}{2 \cdot 9.81}
$$

$$
H_{\max} = \frac{(60.18)^2}{19.62}
$$

$$
H_{\max} \approx \frac{3621.63}{19.62}
$$

$$
H_{\max} \approx 184.59 \text{ m}
$$

### 4. Range

The range is the horizontal distance traveled during the time of flight:

$$
R = x(T) = v_0 \cos \theta \, T
$$

Using the time of flight formula,

$$
R = v_0 \cos \theta \cdot \frac{2 v_0 \sin \theta}{g}
$$

$$
R = \frac{2 v_0^2 \sin \theta \cos \theta}{g}
$$

Using the identity

$$
\sin(2\theta) = 2 \sin \theta \cos \theta
$$

this becomes

$$
R = \frac{v_0^2 \sin(2\theta)}{g}
$$

Now substitute the values:

$$
R = \frac{100^2 \sin(74^\circ)}{9.81}
$$

Using $\sin 74^\circ \approx 0.9613$,

$$
R \approx \frac{10000 \cdot 0.9613}{9.81}
$$

$$
R \approx \frac{9613}{9.81}
$$

$$
R \approx 979.92 \text{ m}
$$

## Final Result

The differential equations of motion are

$$
\frac{d^2 x}{dt^2} = 0
$$

$$
\frac{d^2 y}{dt^2} = -g
$$

The corresponding position functions are

$$
x(t) = 100 \cos 37^\circ \, t
$$

$$
y(t) = 100 \sin 37^\circ \, t - \frac{1}{2}gt^2
$$

Numerically,

$$
x(t) \approx 79.86\, t
$$

$$
y(t) \approx 60.18\, t - 4.905\, t^2
$$

Time of flight:

$$
T \approx 12.27 \text{ s}
$$

Maximum height:

$$
H_{\max} \approx 184.59 \text{ m}
$$

Range:

$$
R \approx 979.92 \text{ m}
$$

## Interpretation

The horizontal motion is uniform because there is no horizontal force. The vertical motion is uniformly accelerated downward due to gravity. The projectile rises until its vertical velocity becomes zero, then falls symmetrically back to the ground. The total flight time is twice the ascent time because the launch and landing heights are the same.