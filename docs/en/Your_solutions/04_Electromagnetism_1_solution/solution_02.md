# Task 02 – Electric Potential at the Center of a Square

## Problem Statement

Point charges of $+1\,\mathrm{C}$, $-2\,\mathrm{C}$, $+3\,\mathrm{C}$, and $-4\,\mathrm{C}$ are placed in order at the corners of a square of side $1.0\,\mathrm{m}$. Determine the electric potential at the center of the square.

## Theory

The electric potential due to a point charge is

$$
V = k \frac{q}{r}
$$

Electric potential is a scalar quantity. Therefore, the total potential due to multiple charges is the algebraic sum of the individual contributions:

$$
V_{\text{net}} = \sum_i k \frac{q_i}{r_i}
$$

At the center of the square, each corner is the same distance from the center. That makes the calculation especially simple.

## Step-by-Step Solution

### Distance from the center to a corner

The square side is

$$
a = 1.0\,\mathrm{m}
$$

The diagonal is

$$
d = a\sqrt{2}
$$

Hence the center-to-corner distance is

$$
r = \frac{a\sqrt{2}}{2}
$$

Thus

$$
r = \frac{\sqrt{2}}{2}\,\mathrm{m}
$$

### Sum of the charges

The four charges are

$$
q_1 = +1\,\mathrm{C}
$$

$$
q_2 = -2\,\mathrm{C}
$$

$$
q_3 = +3\,\mathrm{C}
$$

$$
q_4 = -4\,\mathrm{C}
$$

Their algebraic sum is

$$
q_{\text{tot}} = 1 - 2 + 3 - 4
$$

$$
q_{\text{tot}} = -2\,\mathrm{C}
$$

### Total electric potential

Because all charges are the same distance from the center,

$$
V = k \frac{q_1 + q_2 + q_3 + q_4}{r}
$$

Therefore

$$
V = k \frac{-2}{\sqrt{2}/2}
$$

Using

$$
\frac{1}{\sqrt{2}/2} = \sqrt{2}
$$

the expression becomes

$$
V = -2\sqrt{2}\,k
$$

Substituting

$$
k = 8.99 \times 10^9\,\mathrm{N\,m^2/C^2}
$$

gives

$$
V = -2\sqrt{2} \cdot 8.99 \times 10^9
$$

$$
V \approx -2.828 \cdot 8.99 \times 10^9
$$

$$
V \approx -2.54 \times 10^{10}\,\mathrm{V}
$$

## Final Result

The electric potential at the center of the square is

$$
V \approx -2.54 \times 10^{10}\,\mathrm{V}
$$

## Interpretation

The result is negative because the total algebraic charge contribution is negative. Unlike force, potential has no direction and is added as an ordinary scalar. This makes potential calculations much simpler than force calculations in many multi-charge systems.