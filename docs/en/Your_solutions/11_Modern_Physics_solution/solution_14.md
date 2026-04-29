# Task 11.14 – Hadamard Gate and a Superposition State

## Problem Statement

Apply the Hadamard gate to $|0\rangle$ and show that it produces $(|0\rangle+|1\rangle)/\sqrt{2}$. Explain why this is a superposition.

## Theory

Matrix multiplication gives the new qubit state. The result is a linear combination of both basis states with equal amplitudes.

$$
|0\rangle=\begin{pmatrix}1\\0\end{pmatrix}
$$

$$
H=\frac{1}{\sqrt{2}}\begin{pmatrix}1&1\\1&-1\end{pmatrix}
$$

## Step-by-Step Solution

$$
H|0\rangle=\frac{1}{\sqrt{2}}\begin{pmatrix}1&1\\1&-1\end{pmatrix}\begin{pmatrix}1\\0\end{pmatrix}
$$

$$
H|0\rangle=\frac{1}{\sqrt{2}}\begin{pmatrix}1\\1\end{pmatrix}
$$

$$
|\psi\rangle=\frac{1}{\sqrt{2}}|0\rangle+\frac{1}{\sqrt{2}}|1\rangle
$$

## Final Result

$$
|\psi\rangle=\frac{1}{\sqrt{2}}|0\rangle+\frac{1}{\sqrt{2}}|1\rangle
$$

## Interpretation

The state is a superposition because it is not purely $|0\rangle$ or purely $|1\rangle$; measurement in the computational basis gives either outcome with probability $1/2$.
