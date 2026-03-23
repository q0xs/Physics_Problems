# Task 07 – Dynamics with Friction for Two Blocks

## Problem Statement

A block of mass $5\ \mathrm{kg}$ is placed on top of a block of mass $10\ \mathrm{kg}$. A horizontal force of $45\ \mathrm{N}$ is applied to the $10\ \mathrm{kg}$ block. The $5\ \mathrm{kg}$ block is tied to a wall. The coefficient of kinetic friction between all moving surfaces is $0.2$.

Determine the acceleration of the $10\ \mathrm{kg}$ block.

## Theory

The lower block moves relative to both:

1. the upper block,
2. the floor.

Therefore two kinetic friction forces oppose the motion of the $10\ \mathrm{kg}$ block.

### Friction between the two blocks

The normal force exerted by the upper block on the lower block is

$$
N_{12} = m_1 g
$$

so the kinetic friction magnitude is

$$
f_{12} = \mu_k N_{12} = \mu_k m_1 g
$$

### Friction between the lower block and the floor

The floor supports both masses, so the normal force from the floor is

$$
N_f = (m_1 + m_2) g
$$

Hence the kinetic friction from the floor is

$$
f_f = \mu_k N_f = \mu_k (m_1 + m_2) g
$$

### Newton's second law for the lower block

If the applied force is $F$, then

$$
F - f_{12} - f_f = m_2 a
$$

## Step-by-Step Solution

### 1. Define the masses

Upper block:

$$
m_1 = 5\ \mathrm{kg}
$$

Lower block:

$$
m_2 = 10\ \mathrm{kg}
$$

Applied force:

$$
F = 45\ \mathrm{N}
$$

Coefficient of kinetic friction:

$$
\mu_k = 0.2
$$

Use

$$
g = 9.81\ \mathrm{m/s^2}
$$

### 2. Friction between upper and lower block

The normal force is

$$
N_{12} = m_1 g = 5 \cdot 9.81 = 49.05\ \mathrm{N}
$$

Thus,

$$
f_{12} = \mu_k N_{12} = 0.2 \cdot 49.05 = 9.81\ \mathrm{N}
$$

This friction acts to the left on the lower block.

### 3. Friction between lower block and floor

The floor supports the total weight:

$$
N_f = (m_1 + m_2) g = (5 + 10) \cdot 9.81 = 147.15\ \mathrm{N}
$$

Hence,

$$
f_f = \mu_k N_f = 0.2 \cdot 147.15 = 29.43\ \mathrm{N}
$$

This also acts to the left on the lower block.

### 4. Net force on the lower block

The net horizontal force is

$$
F_{\text{net}} = 45 - 9.81 - 29.43
$$

$$
F_{\text{net}} = 5.76\ \mathrm{N}
$$

### 5. Acceleration of the lower block

Apply Newton's second law:

$$
F_{\text{net}} = m_2 a
$$

Thus,

$$
a = \frac{5.76}{10}
$$

$$
a = 0.576\ \mathrm{m/s^2}
$$

## Final Result

The acceleration of the $10\ \mathrm{kg}$ block is

$$
a \approx 0.58\ \mathrm{m/s^2}
$$

## Interpretation

Two friction forces resist the motion of the lower block: one due to sliding against the upper block and one due to sliding on the floor. Because the upper block is tied to the wall, relative motion occurs at the contact surface, so kinetic friction must be included there as well.