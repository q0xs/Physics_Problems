# Task 06.02 – Equivalent Resistances from Three One-Ohm Resistors

## Problem Statement

Using exactly three $1\,\Omega$ resistors, list all unique equivalent resistances that can be made.

## Theory

All three resistors may be connected in series, in parallel, or in mixed series-parallel combinations. Symmetric rearrangements that give the same value are counted once.

$$
R_s=R_1+R_2+R_3
$$

$$
\frac{1}{R_p}=\sum_i\frac{1}{R_i}
$$

## Step-by-Step Solution

$$
R_{sss}=1+1+1=3\,\Omega
$$

$$
R_{ppp}=\frac{1}{3}\,\Omega
$$

$$
R_{(2s)||1}=\frac{(2)(1)}{2+1}=\frac{2}{3}\,\Omega
$$

$$
R_{(2p)+1}=\frac{1}{2}+1=\frac{3}{2}\,\Omega
$$

## Final Result

The unique values are $\frac{1}{3}\,\Omega$, $\frac{2}{3}\,\Omega$, $\frac{3}{2}\,\Omega$, and $3\,\Omega$.

## Interpretation

These values show that mixed networks can produce resistances smaller or larger than a single resistor depending on how current paths are arranged.
