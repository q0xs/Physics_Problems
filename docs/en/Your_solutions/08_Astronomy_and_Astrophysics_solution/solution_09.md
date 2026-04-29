# Task 08.09 – Aristarchus' Sun Distance Estimate

## Problem Statement

At half-Moon, $\theta=89.85^\circ$, apparent angular diameter $\alpha=0.53^\circ$, and Earth-Moon distance $3.84\times10^5\text{ km}$. Find Earth-Sun distance, Sun diameter, diameter ratio, and sensitivity to $89.75^\circ$.

## Theory

At dichotomy the Moon angle is a right angle, so the Earth-Sun distance is the hypotenuse of a right triangle. The small-angle formula converts angular diameter to true diameter.

$$
d_{ES}=\frac{d_{EM}}{\cos\theta}
$$

$$
D_S=\alpha d_{ES}
$$

## Step-by-Step Solution

$$
d_{ES}=\frac{3.84\times10^5}{\cos89.85^\circ}=1.47\times10^8\text{ km}
$$

$$
\alpha=0.53^\circ=9.25\times10^{-3}\text{ rad}
$$

$$
D_S=(9.25\times10^{-3})(1.47\times10^8)=1.36\times10^6\text{ km}
$$

$$
\frac{D_M}{D_S}=\frac{d_{EM}}{d_{ES}}=2.62\times10^{-3}
$$

$$
d_{ES}(89.75^\circ)=8.80\times10^7\text{ km}
$$

## Final Result

$d_{ES}=1.47\times10^8\text{ km}$, $D_S=1.36\times10^6\text{ km}$, and $D_M/D_S=2.62\times10^{-3}$. The alternate angle gives $8.80\times10^7\text{ km}$.

## Interpretation

The method is extremely sensitive because the angle is very close to $90^\circ$, where small angular errors cause large distance changes.
