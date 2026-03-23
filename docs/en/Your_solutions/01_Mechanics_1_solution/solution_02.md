# Task 02 – Range Optimization

## Problem Statement

For projectile motion, show analytically that the range

$$
R(\theta) = \frac{v_0^2 \sin(2\theta)}{g}
$$

is maximized, for fixed initial speed $v_0$, at a launch angle of $45^\circ$.

## Theory

For projectile motion on level ground without air resistance, the range depends on the launch angle $\theta$ through the function

$$
R(\theta) = \frac{v_0^2}{g}\sin(2\theta)
$$

where $v_0$ and $g$ are constants.

Since $\frac{v_0^2}{g}$ is constant for a given launch speed and gravitational field, maximizing $R(\theta)$ reduces to maximizing $\sin(2\theta)$.

A differentiable function has a local extremum where its derivative vanishes, provided the point lies inside the domain. The nature of the extremum can then be checked using the second derivative.

## Step-by-Step Solution

The range function is

$$
R(\theta) = \frac{v_0^2}{g}\sin(2\theta)
$$

### 1. Differentiate with respect to $\theta$

Since $\frac{v_0^2}{g}$ is constant,

$$
\frac{dR}{d\theta} = \frac{v_0^2}{g} \frac{d}{d\theta}\sin(2\theta)
$$

Using the chain rule,

$$
\frac{d}{d\theta}\sin(2\theta) = 2\cos(2\theta)
$$

Therefore,

$$
\frac{dR}{d\theta} = \frac{2v_0^2}{g}\cos(2\theta)
$$

To find critical points, set the derivative equal to zero:

$$
\frac{2v_0^2}{g}\cos(2\theta) = 0
$$

Since $\frac{2v_0^2}{g} \neq 0$, this gives

$$
\cos(2\theta) = 0
$$

The solutions are

$$
2\theta = 90^\circ + 180^\circ k
$$

for integer $k$. Hence

$$
\theta = 45^\circ + 90^\circ k
$$

For projectile motion, the physically meaningful interval is

$$
0^\circ \leq \theta \leq 90^\circ
$$

Within this interval, the only critical point is

$$
\theta = 45^\circ
$$

### 2. Verify that this gives a maximum

Differentiate once more:

$$
\frac{d^2R}{d\theta^2} = \frac{2v_0^2}{g} \frac{d}{d\theta}\cos(2\theta)
$$

Again using the chain rule,

$$
\frac{d}{d\theta}\cos(2\theta) = -2\sin(2\theta)
$$

Thus,

$$
\frac{d^2R}{d\theta^2} = -\frac{4v_0^2}{g}\sin(2\theta)
$$

At $\theta = 45^\circ$,

$$
\sin(2\theta) = \sin(90^\circ) = 1
$$

so

$$
\frac{d^2R}{d\theta^2}\bigg|_{\theta=45^\circ} = -\frac{4v_0^2}{g} < 0
$$

A negative second derivative implies a local maximum.

### 3. Compute the maximum value

Substitute $\theta = 45^\circ$ into the range formula:

$$
R_{\max} = \frac{v_0^2 \sin(90^\circ)}{g}
$$

Since $\sin(90^\circ)=1$,

$$
R_{\max} = \frac{v_0^2}{g}
$$

## Final Result

The range is maximized when

$$
\theta = 45^\circ
$$

and the maximum range is

$$
R_{\max} = \frac{v_0^2}{g}
$$

## Interpretation

The factor controlling the angular dependence of the range is $\sin(2\theta)$. This function reaches its largest possible value, equal to $1$, when $2\theta = 90^\circ$, which gives $\theta = 45^\circ$.

This result is valid only under the ideal assumptions of:

1. no air resistance,
2. launch and landing at the same height,
3. constant gravitational acceleration.

Under these assumptions, complementary angles such as $30^\circ$ and $60^\circ$ produce the same range because they have the same value of $\sin(2\theta)$.