# Task 11.13 – Probability in a One-Dimensional Box

## Problem Statement

For ground-state wavefunction $\Psi(x)=\sqrt{2/L}\sin(\pi x/L)$, find probabilities in $0\le x\le L/4$ and $L/4\le x\le L/2$.

## Theory

Probability is the integral of $|\Psi|^2$ over the interval.

$$
P(a,b)=\int_a^b |\Psi(x)|^2 dx
$$

$$
P(0,a)=\frac{a}{L}-\frac{\sin(2\pi a/L)}{2\pi}
$$

## Step-by-Step Solution

$$
P(0,L/4)=\frac{1}{4}-\frac{1}{2\pi}=0.0908
$$

$$
P(L/4,L/2)=\frac{1}{2}-\left(\frac{1}{4}-\frac{1}{2\pi}\right)=0.409
$$

## Final Result

$P(0,L/4)=0.0908$ and $P(L/4,L/2)=0.409$. The second interval is more likely.

## Interpretation

The ground-state probability density is largest near the center of the box, so the region closer to the center has higher probability.
