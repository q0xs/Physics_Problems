# Task 06.05 – Kirchhoff's Laws in a Two-Loop Circuit

## Problem Statement

Using Kirchhoff's laws, find currents through $R_1=20\,\Omega$, $R_2=10\,\Omega$, and the right source branch for the two-loop circuit with $\mathcal{E}_1=4.5\text{ V}$, $\mathcal{E}_2=9\text{ V}$, and internal resistances $1\,\Omega$.

## Theory

A convenient method is nodal analysis between the top node and bottom node. Each source branch is represented by its source voltage and series resistance. Current signs indicate whether the assumed direction matches the actual current.

$$
\sum I_{\text{leaving node}}=0
$$

## Step-by-Step Solution

Let $V$ be the top-node potential relative to the bottom node. With downward current positive,

$$
\frac{V-4.5}{21}+\frac{V}{10}+\frac{V-9}{1}=0
$$

$$
V=8.03\text{ V}
$$

$$
I_1=\frac{V-4.5}{21}=0.168\text{ A}
$$

$$
I_2=\frac{V}{10}=0.803\text{ A}
$$

$$
I_3=V-9=-0.971\text{ A}
$$

## Final Result

$I_1=0.168\text{ A}$, $I_2=0.803\text{ A}$, and the right branch current has magnitude $0.971\text{ A}$ opposite the assumed downward direction.

## Interpretation

The negative sign for the right branch means the $9\text{ V}$ source drives current upward through that branch in the chosen sign convention.
