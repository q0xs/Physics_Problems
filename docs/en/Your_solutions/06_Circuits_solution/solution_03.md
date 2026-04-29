# Task 06.03 – Equivalent Resistance of a Mixed Five-Ohm Network

## Problem Statement

Calculate the equivalent resistance for the first mixed circuit diagram in which all resistors have resistance $5\,\Omega$.

## Theory

The network can be treated by nodal analysis. Assign $1\text{ V}$ across the terminals, solve the internal node voltages, and compute the total current. Then $R_{\text{eq}}=V/I$.

$$
R_{\text{eq}} = \frac{V}{I_{\text{total}}}
$$

## Step-by-Step Solution

Using nodal analysis with each resistor equal to $R$, the dimensionless equivalent resistance of the network is

$$
R_{\text{eq}} = \frac{16}{21}R
$$

For $R=5\,\Omega$,

$$
R_{\text{eq}} = \frac{16}{21}(5)=3.81\,\Omega
$$

## Final Result

$$
R_{\text{eq}} = 3.81\,\Omega
$$

## Interpretation

The equivalent resistance is less than $5\,\Omega$ because a direct bottom branch and additional upper branches provide parallel current paths.
