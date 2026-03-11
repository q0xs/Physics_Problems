# Physics Problem: Infinite Series

## 1. Key Definitions and Formulas

An ant starts at the origin and moves according to the pattern:

- \(1\) m east,
- \(\frac{1}{2}\) m north,
- \(\frac{1}{3}\) m west,
- \(\frac{1}{4}\) m south,
- \(\frac{1}{5}\) m east,
- and so on.

To find the final position, we separate the motion into:
- horizontal displacement,
- vertical displacement.

Two known infinite series are useful here:

### Leibniz series

$$
1 - \frac{1}{3} + \frac{1}{5} - \frac{1}{7} + \cdots = \frac{\pi}{4}
$$

### Alternating harmonic series

$$
1 - \frac{1}{2} + \frac{1}{3} - \frac{1}{4} + \cdots = \ln 2
$$

---

## 2. Solving the Problem

We split the ant’s movement into horizontal and vertical parts.

---

## 3. Step-by-Step Derivation

### Horizontal displacement

The horizontal motion is:

$$
1 - \frac{1}{3} + \frac{1}{5} - \frac{1}{7} + \cdots
$$

This is exactly the Leibniz series, so:

$$
x = \frac{\pi}{4}
$$

### Vertical displacement

The vertical motion is:

$$
\frac{1}{2} - \frac{1}{4} + \frac{1}{6} - \frac{1}{8} + \cdots
$$

Factor out \(\frac{1}{2}\):

$$
\frac{1}{2}\left(1 - \frac{1}{2} + \frac{1}{3} - \frac{1}{4} + \cdots\right)
$$

The series inside the parentheses is the alternating harmonic series:

$$
1 - \frac{1}{2} + \frac{1}{3} - \frac{1}{4} + \cdots = \ln 2
$$

So:

$$
y = \frac{1}{2}\ln 2
$$

Thus the final position is:

$$
\left(\frac{\pi}{4}, \frac{1}{2}\ln 2\right)
$$

Approximate values:

$$
\frac{\pi}{4} \approx 0.785
$$

$$
\frac{1}{2}\ln 2 \approx 0.347
$$

---

## 4. Final Answer

The final position of the ant is:

$$
\left(\frac{\pi}{4}, \frac{1}{2}\ln 2\right)
$$

approximately:

$$
(0.785,\;0.347)
$$

So the ant ends about:
- \(0.785\) m east,
- \(0.347\) m north.
$$