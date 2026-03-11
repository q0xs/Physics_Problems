# Physics Problem: Definite Integrals

## 1. Key Definitions and Formulas

We want to calculate the area under the curve:

$$
f(x) = \sin(x)
$$

from \(x=0\) to \(x=\pi\).

So we need to compute the definite integral:

$$
\int_0^\pi \sin(x)\,dx
$$

The antiderivative of \(\sin(x)\) is:

$$
\int \sin(x)\,dx = -\cos(x)
$$

---

## 2. Solving the Problem

We will use the Fundamental Theorem of Calculus:
1. find the antiderivative,
2. evaluate it at the upper and lower limits.

---

## 3. Step-by-Step Derivation

Start with:

$$
\int_0^\pi \sin(x)\,dx
$$

Use the antiderivative:

$$
\int \sin(x)\,dx = -\cos(x)
$$

So:

$$
\int_0^\pi \sin(x)\,dx = \left[-\cos(x)\right]_0^\pi
$$

This means:

$$
-\cos(\pi) - \left(-\cos(0)\right)
$$

We know:

$$
\cos(\pi) = -1, \qquad \cos(0)=1
$$

Substitute:

$$
-\cos(\pi) = -(-1)=1
$$

and

$$
-\cos(0) = -1
$$

Therefore:

$$
1 - (-1) = 2
$$

---

## 4. Final Answer

$$
\int_0^\pi \sin(x)\,dx = 2
$$