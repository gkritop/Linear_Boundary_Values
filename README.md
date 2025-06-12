# Linear Boundary Values

## Overview

This project solves the time-independent Schrödinger equation for a particle in a one-dimensional infinite potential well using the Numerov algorithm. Numerical wavefunctions and energy levels were computed and compared to analytical solutions.

Part of the **Computational Physics** course at the **Physics Department, University of Crete**.

## Problem Statement

We solve the Schrödinger equation for a particle in an infinite potential well, finding allowed energy levels and wavefunctions numerically, then verify against exact solutions. The method is extended to more complex potentials.

## Methodology

- Applied the **Numerov algorithm** to solve the differential equation.
- Modeled infinite potential barriers at the well edges.
- Used a shooting method with bisection to find energy eigenvalues satisfying boundary conditions.

### Implementation

- Discretized space on a uniform grid.
- Imposed Dirichlet boundary conditions (wavefunction zero at edges).
- Iteratively adjusted energies to meet boundary conditions.
- Normalized computed wavefunctions.

### Analytical Comparison

- Derived analytical energy eigenvalues and wavefunctions.
- Compared numerical results to exact solutions and measured deviations.

## Linear Boundary Value Problems

Key activities included:

- Developing algorithms combining Numerov, shooting, and bisection to find eigenvalues and wavefunctions.
- Solving the infinite square well, computing and normalizing the first four states, confirming close match to theory.
- Extending to the finite square well with adjusted boundary conditions and wavefunction matching.
- Modeling covalent bonding in a simplified hydrogen molecular ion by creating a double-well potential and studying energy dependence on well separation.
- Applying the method to the quantum harmonic oscillator and verifying the evenly spaced energy spectrum.
- Solving the radial Schrödinger equation with backward integration and Taylor expansions, obtaining accurate radial eigenvalues and functions.

## Results

- Computed wavefunctions and energies for the first four states.
- Numerical results matched analytical solutions with minimal errors.

## Conclusion

- Numerov is effective for 1D Schrödinger equation problems.
- Results closely match analytical solutions.
- The method adapts well to more complex potentials and boundary conditions.

## Usage

All work is in `LBV_Problems.ipynb`. Run in any Jupyter environment with Python, NumPy, and Matplotlib installed.

## Acknowledgements

Developed by **Giorgos Kritopoulos** for the Computational Physics course, Physics Department, University of Crete.  
Date: March 20, 2025
