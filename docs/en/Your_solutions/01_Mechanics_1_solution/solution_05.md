# Task 05 – Relative Velocity

## Problem Statement

A river flows east at $2 \text{ m/s}$. A boat can travel at $5 \text{ m/s}$ in still water and wants to go directly north across the river.

Determine:

1. The direction in which the boat must head.
2. The time required to cross a river that is $200 \text{ m}$ wide.

## Theory

The boat's actual velocity relative to the ground is the vector sum of:

1. the boat's velocity relative to the water,
2. the water's velocity relative to the ground.

Thus,

$$
\vec v_{\text{boat, ground}} = \vec v_{\text{boat, water}} + \vec v_{\text{water, ground}}
$$

To move directly north, the east-west component of the ground velocity must be zero.

## Step-by-Step Solution

Take east as the positive $x$ direction and north as the positive $y$ direction.

The river velocity is

$$
\vec v_{\text{water, ground}} = (2,0)
$$

The boat speed relative to the water has magnitude $5 \text{ m/s}$. Let the boat head at an angle $\theta$ west of north. Then its velocity relative to the water has components

$$
\vec v_{\text{boat, water}} = (-5\sin\theta, 5\cos\theta)
$$

The ground velocity is therefore

$$
\vec v_{\text{boat, ground}} = (-5\sin\theta + 2,\; 5\cos\theta)
$$

### 1. Condition for going directly north

To go directly north, the horizontal component must vanish:

$$
-5\sin\theta + 2 = 0
$$

Thus,

$$
5\sin\theta = 2
$$

$$
\sin\theta = \frac{2}{5}
$$

So the required heading angle is

$$
\theta = \sin^{-1}\left(\frac{2}{5}\right)
$$

Numerically,

$$
\theta \approx 23.58^\circ
$$

Therefore the boat must head

$$
23.58^\circ \text{ west of north}
$$

### 2. Northward crossing speed

The northward component of the boat's ground velocity is

$$
v_{\text{north}} = 5\cos\theta
$$

Using

$$
\sin\theta = \frac{2}{5}
$$

one gets

$$
\cos\theta = \sqrt{1-\sin^2\theta}
$$

$$
\cos\theta = \sqrt{1-\left(\frac{2}{5}\right)^2}
$$

$$
\cos\theta = \sqrt{1-\frac{4}{25}}
$$

$$
\cos\theta = \sqrt{\frac{21}{25}} = \frac{\sqrt{21}}{5}
$$

Hence

$$
v_{\text{north}} = 5 \cdot \frac{\sqrt{21}}{5} = \sqrt{21}
$$

So

$$
v_{\text{north}} \approx 4.58 \text{ m/s}
$$

### 3. Crossing time

Time is distance divided by speed:

$$
t = \frac{200}{v_{\text{north}}}
$$

Thus,

$$
t = \frac{200}{\sqrt{21}}
$$

Numerically,

$$
t \approx \frac{200}{4.58}
$$

$$
t \approx 43.64 \text{ s}
$$

## Final Result

The boat must head

$$
\theta = \sin^{-1}\left(\frac{2}{5}\right) \approx 23.58^\circ
$$

west of north.

The crossing time is

$$
t = \frac{200}{\sqrt{21}} \approx 43.64 \text{ s}
$$

## Interpretation

The boat must aim upstream, that is, slightly west of north, so that the river's eastward current is exactly canceled by the westward component of the boat's velocity relative to the water. The remaining northward component determines the crossing time.