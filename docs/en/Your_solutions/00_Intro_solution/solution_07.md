# Task 07 – Logic and Series

## Problem Statement

A bicycle is $10$ meters from a wall and moves toward it at a constant speed of $1 \text{ m/s}$. A fly starts from the bicycle's front wheel and flies toward the wall at $2 \text{ m/s}$. When it reaches the wall, it instantly turns around and flies back toward the bicycle. This motion repeats until the bicycle reaches the wall.

Determine the total distance traveled by the fly before it is crushed.

## Theory

At first glance, the motion seems complicated because the fly performs infinitely many back-and-forth trips. However, the key idea is that the bicycle reaches the wall in a finite amount of time, and during that entire time the fly continues moving at a constant speed.

The distance traveled by an object moving at constant speed is

$$
d = vt
$$

where:

$d$ is distance

$v$ is speed

$t$ is time

Therefore, if the total travel time of the fly is known, the total distance can be found directly.

## Step-by-Step Solution

### Time for the Bicycle to Reach the Wall

The bicycle starts $10$ meters away from the wall and moves at a speed of

$$
v_{\text{bike}} = 1 \text{ m/s}
$$

The time needed to reach the wall is

$$
t = \frac{d}{v}
$$

Substitute the known values:

$$
t = \frac{10}{1}
$$

$$
t = 10 \text{ s}
$$

So the bicycle reaches the wall after $10$ seconds.

### Distance Traveled by the Fly

The fly moves continuously during these same $10$ seconds with speed

$$
v_{\text{fly}} = 2 \text{ m/s}
$$

Use the distance formula:

$$
d_{\text{fly}} = v_{\text{fly}} t
$$

Substitute the values:

$$
d_{\text{fly}} = 2 \cdot 10
$$

$$
d_{\text{fly}} = 20 \text{ m}
$$

## Final Result

The total distance traveled by the fly is

$$
20 \text{ m}
$$

## Interpretation

Although the fly changes direction infinitely many times, the total flight time is finite because the bicycle reaches the wall after exactly $10$ seconds. Since the fly never stops moving during that interval, its total distance is simply its speed multiplied by the total time. This problem is a classic example showing that infinitely many separate motions can still produce a finite total result.