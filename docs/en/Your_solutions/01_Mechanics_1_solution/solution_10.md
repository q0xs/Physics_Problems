# Task 10 – Kinematics of a Point Moving on an Elliptic Helix

## Problem Statement

A point moves according to

$$
\vec{r}(t) = (a \cos(\omega t), b \sin(\omega t), bt)
$$

where $a$, $b$, and $\omega$ are positive constants.

Required:

a) Find the equation of the point's trajectory.

b) Compute the path length of the point from time $t=0$ to $t=t_0$.

c) Draw the trajectory of this point using Python or interactive HTML. Discuss special cases.

## Theory

The motion is given in parametric form:

$$
x(t) = a \cos(\omega t)
$$

$$
y(t) = b \sin(\omega t)
$$

$$
z(t) = bt
$$

The first two coordinates describe periodic motion in the $xy$-plane, while the third coordinate increases linearly with time. Therefore the point moves upward while winding around a cylinder.

To determine the trajectory, the parameter $t$ is eliminated.

The path length of a curve described by $\vec{r}(t)$ on an interval $[t_1,t_2]$ is

$$
L = \int_{t_1}^{t_2} \left|\frac{d\vec r}{dt}\right| \, dt
$$

where $\left|\frac{d\vec r}{dt}\right|$ is the speed.

## Step-by-Step Solution

### a) Equation of the trajectory

The parametric equations are

$$
x = a \cos(\omega t)
$$

$$
y = b \sin(\omega t)
$$

$$
z = bt
$$

From the first two equations,

$$
\frac{x}{a} = \cos(\omega t)
$$

$$
\frac{y}{b} = \sin(\omega t)
$$

Squaring and adding gives

$$
\left(\frac{x}{a}\right)^2 + \left(\frac{y}{b}\right)^2 = \cos^2(\omega t) + \sin^2(\omega t)
$$

Thus,

$$
\frac{x^2}{a^2} + \frac{y^2}{b^2} = 1
$$

This is the equation of an elliptic cylinder.

Since

$$
z = bt
$$

the parameter can also be written as

$$
t = \frac{z}{b}
$$

Substituting into the first two equations gives

$$
x = a \cos\left(\frac{\omega z}{b}\right)
$$

$$
y = b \sin\left(\frac{\omega z}{b}\right)
$$

Therefore the point moves on an elliptic helix lying on the cylinder

$$
\frac{x^2}{a^2} + \frac{y^2}{b^2} = 1
$$

### b) Path length from $t=0$ to $t=t_0$

Differentiate the position vector:

$$
\frac{d\vec r}{dt} = \left(-a\omega \sin(\omega t), \; b\omega \cos(\omega t), \; b\right)
$$

The speed is

$$
\left|\frac{d\vec r}{dt}\right|
=
\sqrt{
\left(-a\omega \sin(\omega t)\right)^2
+
\left(b\omega \cos(\omega t)\right)^2
+
b^2
}
$$

Hence

$$
\left|\frac{d\vec r}{dt}\right|
=
\sqrt{
a^2\omega^2 \sin^2(\omega t)
+
b^2\omega^2 \cos^2(\omega t)
+
b^2
}
$$

Therefore the path length from $0$ to $t_0$ is

$$
L
=
\int_0^{t_0}
\sqrt{
a^2\omega^2 \sin^2(\omega t)
+
b^2\omega^2 \cos^2(\omega t)
+
b^2
}
\, dt
$$

This is the general formula.

A useful equivalent form is

$$
L
=
\int_0^{t_0}
\sqrt{
b^2 + \omega^2 \left(a^2 \sin^2(\omega t) + b^2 \cos^2(\omega t)\right)
}
\, dt
$$

In general, this integral is not elementary.

### Special case: $a=b=R$

If $a=b=R$, then

$$
x = R \cos(\omega t)
$$

$$
y = R \sin(\omega t)
$$

$$
z = Rt
$$

and the speed becomes

$$
\left|\frac{d\vec r}{dt}\right|
=
\sqrt{
R^2\omega^2 \sin^2(\omega t)
+
R^2\omega^2 \cos^2(\omega t)
+
R^2
}
$$

Using

$$
\sin^2(\omega t) + \cos^2(\omega t) = 1
$$

this simplifies to

$$
\left|\frac{d\vec r}{dt}\right|
=
\sqrt{R^2\omega^2 + R^2}
$$

$$
\left|\frac{d\vec r}{dt}\right|
=
R\sqrt{\omega^2+1}
$$

So in this case the speed is constant and

$$
L = R\sqrt{\omega^2+1}\, t_0
$$

### c) Python code for plotting

```python
import numpy as np
import matplotlib.pyplot as plt

a = 3.0
b = 2.0
omega = 1.5
t0 = 10.0

t = np.linspace(0, t0, 1000)

x = a * np.cos(omega * t)
y = b * np.sin(omega * t)
z = b * t

fig = plt.figure(figsize=(8, 6))
ax = fig.add_subplot(111, projection="3d")

ax.plot(x, y, z, linewidth=2)

ax.set_xlabel("x")
ax.set_ylabel("y")
ax.set_zlabel("z")
ax.set_title("Trajectory of the Point")

plt.show()