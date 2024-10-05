# Probability-Distribution
# Project Overview
This project explores the probabilities and distributions of four key random variables derived from rolling a fair die twice. It focuses on the relationships between the sum of the rolls, the maximum value, the absolute difference, and the product of these values. By generating sample spaces and calculating probability distributions for each variable, the project aims to provide a clear understanding of how these outcomes behave.

## Random Variables
- **X**: Sum of the two dice rolls (d1 + d2)
- **Y**: Maximum of the two dice rolls (max{d1, d2})
- **Z**: Absolute difference between the two dice rolls (|d1 − d2|)
- **W**: Product of X and Z (X × Z)

## Objectives
- Generate the sample space for each random variable.
- Create probability distribution tables for X, Y, Z, and W.
- Calculate key probabilities including:
  - P(X ≤ 5)
  - P(Y ≥ 3)
  - P(Z ≠ 0)

## Key Features
- **Sample Space Generation**: Using R’s `expand.grid()` function, all possible outcomes from rolling two dice are captured and used to define the sample spaces for X, Y, Z, and W.
- **Probability Distribution**: The probability distribution for each random variable is computed, providing a comprehensive look at the likelihood of different outcomes.
- **Probability Calculations**: Specific probabilities are calculated to answer questions about the behavior of the random variables, helping to deepen understanding of random events in probability theory.
