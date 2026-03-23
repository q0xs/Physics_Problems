# Task 03 – Path Intersection

## Problem Statement

Alice moves along the path

$$
A(t) = (2+t, 8-3t)
$$

and Bob moves along the path

$$
B(t) = (2t-1, 2t+2)
$$

Determine whether their paths intersect. If they do, determine when and where they collide. If they do not, determine the minimum distance between them and when it occurs.

## Theory

Two moving particles collide if they are at the same position at the same time. Therefore a collision requires

$$
A(t) = B(t)
$$

for the same parameter value $t$.

If no such time exists, the distance between the particles at time $t$ is

$$
d(t) = \|A(t)-B(t)\|
$$

and the minimum distance can be found by minimizing either $d(t)$ or, more conveniently, $d^2(t)$.

## Step-by-Step Solution

### 1. Check for collision

Set the coordinates equal:

$$
2+t = 2t-1
$$

and

$$
8-3t = 2t+2
$$

From the first equation,

$$
2+t = 2t-1
$$

$$
3 = t
$$

From the second equation,

$$
8-3t = 2t+2
$$

$$
6 = 5t
$$

$$
t = \frac{6}{5}
$$

The two equations give different times:

$$
t=3 \neq \frac{6}{5}
$$

Therefore Alice and Bob are never at the same position at the same time. There is no collision.

### 2. Distance between Alice and Bob

Compute the relative position:

$$
A(t)-B(t) = (2+t-(2t-1), \; 8-3t-(2t+2))
$$

Simplify each component:

$$
A(t)-B(t) = (3-t, \; 6-5t)
$$

Hence the squared distance is

$$
d^2(t) = (3-t)^2 + (6-5t)^2
$$

Expand:

$$
(3-t)^2 = 9 - 6t + t^2
$$

$$
(6-5t)^2 = 36 - 60t + 25t^2
$$

So

$$
d^2(t) = 9 - 6t + t^2 + 36 - 60t + 25t^2
$$

$$
d^2(t) = 45 - 66t + 26t^2
$$

### 3. Minimize the squared distance

Differentiate:

$$
\frac{d}{dt}d^2(t) = -66 + 52t
$$

Set the derivative equal to zero:

$$
-66 + 52t = 0
$$

$$
52t = 66
$$

$$
t = \frac{66}{52} = \frac{33}{26}
$$

To confirm that this is a minimum, compute the second derivative:

$$
\frac{d^2}{dt^2}d^2(t) = 52 > 0
$$

So the squared distance is minimized at

$$
t_{\min} = \frac{33}{26}
$$

### 4. Minimum distance

Evaluate the relative position at $t=\frac{33}{26}$:

$$
3 - \frac{33}{26} = \frac{78}{26} - \frac{33}{26} = \frac{45}{26}
$$

$$
6 - 5\cdot \frac{33}{26} = \frac{156}{26} - \frac{165}{26} = -\frac{9}{26}
$$

Thus

$$
d_{\min}^2 = \left(\frac{45}{26}\right)^2 + \left(-\frac{9}{26}\right)^2
$$

$$
d_{\min}^2 = \frac{2025}{676} + \frac{81}{676}
$$

$$
d_{\min}^2 = \frac{2106}{676}
$$

$$
d_{\min}^2 = \frac{81}{26}
$$

Therefore

$$
d_{\min} = \sqrt{\frac{81}{26}} = \frac{9}{\sqrt{26}}
$$

Numerically,

$$
d_{\min} \approx 1.765
$$

### 5. Positions at the time of minimum distance

Alice's position at $t=\frac{33}{26}$:

$$
A\left(\frac{33}{26}\right) = \left(2+\frac{33}{26}, \; 8-3\cdot \frac{33}{26}\right)
$$

$$
A\left(\frac{33}{26}\right) = \left(\frac{85}{26}, \; \frac{109}{26}\right)
$$

Bob's position at the same time:

$$
B\left(\frac{33}{26}\right) = \left(2\cdot \frac{33}{26}-1, \; 2\cdot \frac{33}{26}+2\right)
$$

$$
B\left(\frac{33}{26}\right) = \left(\frac{20}{13}, \; \frac{59}{13}\right)
$$

## Final Result

The paths do not intersect at the same time, so Alice and Bob do not collide.

The minimum distance occurs at

$$
t = \frac{33}{26} \approx 1.269
$$

and the minimum distance is

$$
d_{\min} = \frac{9}{\sqrt{26}} \approx 1.765
$$

At that time,

$$
A\left(\frac{33}{26}\right) = \left(\frac{85}{26}, \frac{109}{26}\right)
$$

$$
B\left(\frac{33}{26}\right) = \left(\frac{20}{13}, \frac{59}{13}\right)
$$

## Interpretation

The equations for the $x$ and $y$ coordinates produce different times for coincidence, so simultaneous collision is impossible. Nevertheless, the particles approach one another, reach a smallest separation, and then move farther apart again. Minimizing the squared distance avoids the square root and leads to the same minimizing time as the actual distance.