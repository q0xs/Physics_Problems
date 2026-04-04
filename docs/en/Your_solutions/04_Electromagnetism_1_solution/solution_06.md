# Task 06 – Electric Field of Two Positive Charges

## Problem Statement

Two point charges are located at

- $+q$ at $(-a,0)$
- $+2q$ at $(a,0)$

Required:

1. Determine the field vector $\vec E(0,y)$, $\vec E(x,0)$, and the general field $\vec E(x,y)$.
2. Determine the conditions for which $E_x = 0$, $E_y = 0$, and $\vec E = 0$.
3. Calculate the field for

$$
a = 0.2\,\mathrm{m}
$$

$$
y = 0.3\,\mathrm{m}
$$

$$
q = 2\,\mu\mathrm{C}
$$

4. Investigate the limit $y \gg a$.

## Theory

The electric field of a point charge $Q$ located at position $\vec r_0$ is

$$
\vec E(\vec r) = kQ \frac{\vec r - \vec r_0}{|\vec r - \vec r_0|^3}
$$

For a system of charges, the total field is the vector sum of the individual fields.

Let the field point be

$$
\vec r = (x,y)
$$

and let the source charges be at

$$
\vec r_1 = (-a,0)
$$

and

$$
\vec r_2 = (a,0)
$$

with charges

$$
q_1 = q
$$

and

$$
q_2 = 2q
$$

## Step-by-Step Solution

### General field $\vec E(x,y)$

The displacement vectors from the charges to the field point are

$$
\vec R_1 = (x+a)\hat i + y\hat j
$$

$$
\vec R_2 = (x-a)\hat i + y\hat j
$$

Their magnitudes are

$$
R_1 = \sqrt{(x+a)^2 + y^2}
$$

$$
R_2 = \sqrt{(x-a)^2 + y^2}
$$

Therefore, the fields due to the two charges are

$$
\vec E_1 = kq \frac{(x+a)\hat i + y\hat j}{\left((x+a)^2 + y^2\right)^{3/2}}
$$

$$
\vec E_2 = 2kq \frac{(x-a)\hat i + y\hat j}{\left((x-a)^2 + y^2\right)^{3/2}}
$$

Hence,

$$
\vec E(x,y) =
kq \frac{(x+a)\hat i + y\hat j}{\left((x+a)^2 + y^2\right)^{3/2}}
+
2kq \frac{(x-a)\hat i + y\hat j}{\left((x-a)^2 + y^2\right)^{3/2}}
$$

Thus the Cartesian components are

$$
E_x =
kq \frac{x+a}{\left((x+a)^2 + y^2\right)^{3/2}}
+
2kq \frac{x-a}{\left((x-a)^2 + y^2\right)^{3/2}}
$$

$$
E_y =
kq \frac{y}{\left((x+a)^2 + y^2\right)^{3/2}}
+
2kq \frac{y}{\left((x-a)^2 + y^2\right)^{3/2}}
$$

### Field on the $y$-axis

Set

$$
x = 0
$$

Then

$$
\vec E(0,y) =
kq \frac{a\hat i + y\hat j}{(a^2 + y^2)^{3/2}}
+
2kq \frac{-a\hat i + y\hat j}{(a^2 + y^2)^{3/2}}
$$

Combine the terms:

$$
\vec E(0,y) =
\frac{kq}{(a^2 + y^2)^{3/2}}
\left(
-a\hat i + 3y\hat j
\right)
$$

Therefore,

$$
E_x(0,y) = -\frac{kqa}{(a^2+y^2)^{3/2}}
$$

$$
E_y(0,y) = \frac{3kqy}{(a^2+y^2)^{3/2}}
$$

### Field on the $x$-axis

Set

$$
y = 0
$$

Then

$$
E_y(x,0) = 0
$$

and

$$
E_x(x,0) =
kq \frac{x+a}{|x+a|^3}
+
2kq \frac{x-a}{|x-a|^3}
$$

So the field on the $x$-axis is

$$
\vec E(x,0) =
\left[
kq \frac{x+a}{|x+a|^3}
+
2kq \frac{x-a}{|x-a|^3}
\right]\hat i
$$

### Condition for $E_y = 0$

From the general expression,

$$
E_y =
kq\,y
\left[
\frac{1}{\left((x+a)^2+y^2\right)^{3/2}}
+
\frac{2}{\left((x-a)^2+y^2\right)^{3/2}}
\right]
$$

The bracket is always positive. Hence,

$$
E_y = 0 \iff y = 0
$$

### Condition for $E_x = 0$

The condition is

$$
\frac{x+a}{\left((x+a)^2+y^2\right)^{3/2}}
+
2\frac{x-a}{\left((x-a)^2+y^2\right)^{3/2}} = 0
$$

A special physically important case is the zero-field point on the $x$-axis. Then

$$
y = 0
$$

and the condition becomes

$$
\frac{1}{(x+a)^2} = \frac{2}{(a-x)^2}
$$

for a point between the charges.

Taking square roots gives

$$
a - x = \sqrt{2}(x+a)
$$

Solving:

$$
a - x = \sqrt{2}x + \sqrt{2}a
$$

$$
a(1-\sqrt{2}) = x(1+\sqrt{2})
$$

$$
x = -a \frac{\sqrt{2}-1}{\sqrt{2}+1}
$$

Rationalizing yields

$$
x = -a(\sqrt{2}-1)^2
$$

Since

$$
(\sqrt{2}-1)^2 = 3 - 2\sqrt{2}
$$

the zero-field point is

$$
x_0 = -a(3 - 2\sqrt{2})
$$

### Condition for $\vec E = 0$

For the field to vanish completely, both components must vanish:

$$
E_x = 0
$$

and

$$
E_y = 0
$$

Since $E_y = 0$ only when $y=0$, the zero-field point must lie on the $x$-axis. Hence,

$$
\vec E = 0
\iff
\left(x,y\right) =
\left(-a(3 - 2\sqrt{2}),0\right)
$$

### Numerical calculation for $a=0.2\,\mathrm{m}$, $y=0.3\,\mathrm{m}$, $q=2\,\mu\mathrm{C}$

The requested point is $(0,y)$.

Given:

$$
a = 0.2\,\mathrm{m}
$$

$$
y = 0.3\,\mathrm{m}
$$

$$
q = 2 \times 10^{-6}\,\mathrm{C}
$$

Compute

$$
a^2 + y^2 = 0.04 + 0.09 = 0.13
$$

$$
(a^2+y^2)^{3/2} = 0.13^{3/2} \approx 0.04687
$$

Also,

$$
kq = (8.99 \times 10^9)(2 \times 10^{-6}) = 1.798 \times 10^4
$$

Now compute the components:

$$
E_x(0,y) = -\frac{(1.798 \times 10^4)(0.2)}{0.04687}
$$

$$
E_x(0,y) \approx -7.67 \times 10^4\,\mathrm{N/C}
$$

$$
E_y(0,y) = \frac{3(1.798 \times 10^4)(0.3)}{0.04687}
$$

$$
E_y(0,y) \approx 3.45 \times 10^5\,\mathrm{N/C}
$$

Thus,

$$
\vec E(0,0.3) \approx
\left(
-7.67 \times 10^4\,\hat i
+
3.45 \times 10^5\,\hat j
\right)\,\mathrm{N/C}
$$

Its magnitude is

$$
|\vec E| = \sqrt{E_x^2 + E_y^2}
$$

$$
|\vec E| \approx 3.54 \times 10^5\,\mathrm{N/C}
$$

### Far-field limit $y \gg a$

When

$$
y \gg a
$$

the denominator satisfies

$$
(a^2+y^2)^{3/2} \approx y^3
$$

Therefore,

$$
\vec E(0,y) \approx
-\frac{kqa}{y^3}\hat i
+
\frac{3kq}{y^2}\hat j
$$

The dominant term is the vertical term:

$$
\vec E(0,y) \approx \frac{3kq}{y^2}\hat j
$$

This corresponds to the field of an effective total charge

$$
q_{\text{tot}} = 3q
$$

observed from far away.

## Final Result

The general field is

$$
\vec E(x,y) =
kq \frac{(x+a)\hat i + y\hat j}{\left((x+a)^2 + y^2\right)^{3/2}}
+
2kq \frac{(x-a)\hat i + y\hat j}{\left((x-a)^2 + y^2\right)^{3/2}}
$$

On the $y$-axis:

$$
\vec E(0,y) =
\frac{kq}{(a^2+y^2)^{3/2}}
\left(
-a\hat i + 3y\hat j
\right)
$$

On the $x$-axis:

$$
\vec E(x,0) =
\left[
kq \frac{x+a}{|x+a|^3}
+
2kq \frac{x-a}{|x-a|^3}
\right]\hat i
$$

The component conditions are

$$
E_y = 0 \iff y = 0
$$

and

$$
E_x = 0
\iff
\frac{x+a}{\left((x+a)^2+y^2\right)^{3/2}}
+
2\frac{x-a}{\left((x-a)^2+y^2\right)^{3/2}} = 0
$$

The zero field point is

$$
\left(x,y\right) =
\left(-a(3 - 2\sqrt{2}),0\right)
$$

For the numerical data,

$$
\vec E \approx
\left(
-7.67 \times 10^4\,\hat i
+
3.45 \times 10^5\,\hat j
\right)\,\mathrm{N/C}
$$

with magnitude

$$
|\vec E| \approx 3.54 \times 10^5\,\mathrm{N/C}
$$

In the far-field limit,

$$
\vec E(0,y) \approx \frac{3kq}{y^2}\hat j
$$

to leading order.

## Interpretation

The stronger charge $+2q$ shifts the zero-field point away from the midpoint and closer to the weaker charge $+q$. In the far-field region, the system behaves like a single net charge $3q$, which is the expected monopole approximation.