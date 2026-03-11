# Physics Problem: Optimization

## 1. Key Definitions and Formulas

A rectangle is inscribed under the curve

$$
y = 3 - x^2
$$

in the first quadrant.

If the upper-right corner of the rectangle is \((x,y)\), then:
- width = \(x\),
- height = \(y\),
- and because the point lies on the curve:

$$
y = 3 - x^2
$$

The area of the rectangle is:

$$
A = x \cdot y
$$

---

## 2. Solving the Problem

We want to maximize the area, so we:
1. express the area as a function of \(x\),
2. differentiate,
3. find the critical point.

---

## 3. Step-by-Step Derivation

Substitute \(y = 3 - x^2\) into the area formula:

$$
A(x) = x(3 - x^2)
$$

$$
A(x) = 3x - x^3
$$

Differentiate:

$$
A'(x) = 3 - 3x^2
$$

Set the derivative equal to zero:

$$
3 - 3x^2 = 0
$$

Divide by 3:

$$
1 - x^2 = 0
$$

$$
x^2 = 1
$$

$$
x = 1
$$

We take \(x=1\) because we are in the first quadrant.

Now find the height:

$$
y = 3 - x^2 = 3 - 1 = 2
$$

So the rectangle dimensions are:
- width = 1
- height = 2

The maximum area is:

$$
A = 1 \cdot 2 = 2
$$

---

## 4. Final Answer

The rectangle with maximum area has dimensions:

$$
1 \times 2
$$

That is,

$$
\text{width} = 1, \qquad \text{height} = 2
$$

and the maximum area is:

$$
2
$$