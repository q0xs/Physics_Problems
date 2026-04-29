# Task 07.07 – Mean and Standard Deviation of Test Scores

## Problem Statement

Eleven scores are $88,92,79,85,95,81,86,90,83,77,89$. Find the mean and standard deviation, then repeat after removing the highest and lowest scores.

## Theory

The sample standard deviation uses $N-1$ in the denominator because the mean is estimated from the same data.

$$
\bar{x}=\frac{1}{N}\sum_{i=1}^{N}x_i
$$

$$
\sigma=\sqrt{\frac{1}{N-1}\sum_{i=1}^{N}(x_i-\bar{x})^2}
$$

## Step-by-Step Solution

$$
\bar{x}=85.91
$$

$$
\sigma=5.58
$$

Removing $95$ and $77$ leaves nine scores.

$$
\bar{x}_{\text{trim}}=85.89
$$

$$
\sigma_{\text{trim}}=4.31
$$

## Final Result

All scores: mean $85.91$, standard deviation $5.58$. Trimmed scores: mean $85.89$, standard deviation $4.31$.

## Interpretation

Removing extremes leaves the mean almost unchanged but reduces spread.
