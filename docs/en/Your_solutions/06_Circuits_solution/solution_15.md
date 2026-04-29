# Task 06.15 – Equivalent Resistance of a Resistor Cube

## Problem Statement

A cube is made from $12$ identical edge resistors, each of resistance $R$. Find the equivalent resistance between opposite corners.

## Theory

By symmetry, the three nodes adjacent to one corner are at the same potential, and the three nodes adjacent to the opposite corner are also at the same potential. This allows the cube to reduce to three grouped stages.

$$
R_{\text{eq}} = \frac{5}{6}R
$$

## Step-by-Step Solution

The first group has three resistors in parallel, giving $R/3$. The middle group has six resistors connecting the two equipotential node sets, giving $R/6$. The final group again gives $R/3$. Therefore

$$
R_{\text{eq}}=\frac{R}{3}+\frac{R}{6}+\frac{R}{3}=\frac{5R}{6}
$$

## Final Result

$$
R_{\text{eq}}=\frac{5}{6}R
$$

## Interpretation

Symmetry is essential; it identifies equipotential nodes and prevents the cube from being treated as a simple series-parallel chain.
