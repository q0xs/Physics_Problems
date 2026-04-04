# Task 11 – Animation of Two-Slit Interference

## Problem Statement

Prepare an HTML animation of Young's double-slit experiment, where two slits act as coherent point sources. The resulting displacement is

$$
u(\vec{r},t) = \frac{A}{|\vec{r}-\vec{r_1}|} \sin(k |\vec{r} - \vec{r_1}| - \omega t) + \frac{A}{|\vec{r}-\vec{r_2}|} \sin(k |\vec{r} - \vec{r_2}| - \omega t)
$$

The user should be able to change the slit separation

$$
d = |\vec{r_1} - \vec{r_2}|
$$

and the wavelength $\lambda$. The interference pattern should be visualized in real time.

## Theory

Let the two slit positions be $\vec{r_1}$ and $\vec{r_2}$. At an observation point $\vec{r}$, the distances to the slits are

$$
R_1 = |\vec{r} - \vec{r_1}|
$$

and

$$
R_2 = |\vec{r} - \vec{r_2}|
$$

The total displacement is

$$
u(\vec{r},t) = \frac{A}{R_1} \sin(kR_1 - \omega t) + \frac{A}{R_2} \sin(kR_2 - \omega t)
$$

with

$$
k = \frac{2\pi}{\lambda}
$$

and

$$
\omega = 2\pi f
$$

Because the two sources are coherent, their relative phase difference is determined only by the path-length difference

$$
\Delta R = R_2 - R_1
$$

Constructive interference occurs approximately when

$$
\Delta R = m \lambda
$$

and destructive interference occurs approximately when

$$
\Delta R = \left(m + \frac{1}{2}\right)\lambda
$$

where $m$ is an integer.

## Step-by-Step Solution

### Source Geometry

The two slits are placed symmetrically about the center line. If the distance between them is $d$, then the source coordinates are chosen as

$$
\vec{r_1} = \left(x_0, y_0 - \frac{d}{2}\right)
$$

$$
\vec{r_2} = \left(x_0, y_0 + \frac{d}{2}\right)
$$

### Real-Time Field Computation

For each point on the display grid, the code computes

$$
u(\vec{r},t) = u_1(\vec{r},t) + u_2(\vec{r},t)
$$

and maps the instantaneous displacement to a color scale.

### Effect of Slit Separation

Increasing $d$ changes the path difference more rapidly across the screen. As a result, the interference fringes become more closely spaced.

### Effect of Wavelength

Increasing $\lambda$ reduces the wave number $k$. This broadens the fringe spacing and changes the time evolution of the field.

## Final Result

The following HTML file implements:

- two coherent point sources,
- a slider for slit separation $d$,
- a slider for wavelength $\lambda$,
- real-time visualization of the resulting interference pattern.

## Interpretation

Young's experiment demonstrates interference as a direct consequence of superposition. The geometry of the source separation and the wavelength together determine the fringe structure observed on the screen.
