# Task 06.04 – Equivalent Resistance of a Second Mixed Network

## Problem Statement

Calculate the equivalent resistance for the second mixed circuit diagram in which all resistors have resistance $10\,\Omega$.

## Theory

The rightmost resistor is in series with a two-branch network. The upper branch has two series resistors, while the lower branch has one resistor followed by two parallel resistors.

$$
R_{\parallel}=\frac{R_aR_b}{R_a+R_b}
$$

## Step-by-Step Solution

$$
R_{\text{top}}=10+10=20\,\Omega
$$

$$
R_{\text{lower}}=10+(10\parallel10)=10+5=15\,\Omega
$$

$$
R_{\text{left}}=20\parallel15=\frac{(20)(15)}{20+15}=8.57\,\Omega
$$

$$
R_{\text{eq}}=8.57+10=18.57\,\Omega
$$

## Final Result

$$
R_{\text{eq}}=18.57\,\Omega
$$

## Interpretation

The final series resistor forces all current through it, so it is added after reducing the left network.
