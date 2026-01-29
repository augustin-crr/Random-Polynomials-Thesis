# Master's Thesis: Random Polynomials (Roots Analysis)

This repository contains the research work and theoretical derivations from my Master 1 thesis at the University of Lille, conducted under the supervision of M. Raphaël Butez. The project focuses on the study of the number of real roots of random polynomials, a field at the intersection of probability, complex analysis, and geometry.

## Abstract
The central objective of this work is to determine the expected number of real zeros ($E_n$) for a polynomial of degree $n$ whose coefficients are independent and identically distributed (i.i.d.) Gaussian random variables. The thesis provides a detailed derivation of the **Kac Formula** (1943) through two distinct methodologies:
1. **Analytical Approach**: Using Gaussian random vectors and integral formulas for the expectation of zeros.
2. **Geometric Approach**: Leveraging elementary geometry and the length of curves in the plane to reach the same asymptotic result.

## Key Theoretical Results
- **Kac's Formula**: Derivation of the exact integral expression for the expected number of real roots.
- **Asymptotic Behavior**: Proof that for large $n$, the expected number of real roots grows as $\frac{2}{\pi} \ln(n)$.
- **Stochastic Modeling**: Analysis of Gaussian random vectors and their properties in the context of random algebraic equations.

## Repository Structure
- `TER_CARRE_Augustin.pdf`: The full Master's thesis (in French).
- `src/`: (Optional) Contains scripts used for root distribution simulations (Matlab/Python).

## Technologies & Mathematics
- **Concepts**: Stochastic processes, Gaussian fields, Complex Analysis, Asymptotic Analysis.
- **Keywords**: Kac Formula, Real Zeros, Random Polynomials.

## References
Kac, M. (1943). *On the average number of real roots of a random algebraic equation*.
