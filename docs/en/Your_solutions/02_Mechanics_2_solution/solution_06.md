# Task 06 – Rebound Height with Energy Dissipation

## Problem Statement

A tennis ball is dropped from a height of $2.0\ \mathrm{m}$. After each bounce, it loses $30\%$ of its mechanical energy.

Determine the height reached after the second bounce.

## Theory

The mechanical energy of the ball just before impact is proportional to its height above the ground:

$$
E = mgh
$$

If after each bounce the ball retains only $70\%$ of its energy, then the rebound height is also reduced to $70\%$ of the previous height, because $m$ and $g$ remain constant.

Thus,

$$
h_{n+1} = 0.70 h_n
$$

## Step-by-Step Solution

### 1. Initial height

The initial height is

$$
h_0 = 2.0\ \mathrm{m}
$$

### 2. Height after the first bounce

Since the ball retains $70\%$ of its energy,

$$
h_1 = 0.70 h_0
$$

Therefore,

$$
h_1 = 0.70 \cdot 2.0 = 1.4\ \mathrm{m}
$$

### 3. Height after the second bounce

Apply the same reduction again:

$$
h_2 = 0.70 h_1
$$

$$
h_2 = 0.70 \cdot 1.4 = 0.98\ \mathrm{m}
$$

Equivalently,

$$
h_2 = (0.70)^2 \cdot 2.0
$$

$$
h_2 = 0.49 \cdot 2.0 = 0.98\ \mathrm{m}
$$

## Final Result

After the second bounce, the ball rises to

$$
h_2 = 0.98\ \mathrm{m}
$$

## Interpretation

Because the rebound height is proportional to the remaining mechanical energy, the same percentage loss of energy after each bounce corresponds to the same percentage reduction in height. The sequence of heights forms a geometric progression.