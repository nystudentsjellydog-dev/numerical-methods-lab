# Numerical Methods Lab

## Overview
This repository contains MATLAB implementations of several core topics in numerical analysis, including least-squares approximation, polynomial interpolation, finite-difference methods, eigenvector analysis, and error behavior across different grid sizes.

The project focuses on both computation and interpretation: how numerical methods are implemented, how their outputs compare with exact solutions, and how approximation quality changes as the discretization or interpolation setup varies.

## Topics Covered
- least-squares polynomial fitting
- polynomial interpolation of discontinuous functions
- conditioning behavior in high-degree interpolation
- finite-difference solutions to boundary value problems
- numerical vs. analytical eigenvector comparison
- error analysis under different grid sizes

## Methods
This repository includes MATLAB code for:

### 1. Least-Squares Approximation
Fitting a cubic polynomial to data using different subsets of sample points and comparing the resulting coefficients.

### 2. Polynomial Interpolation
Constructing interpolation polynomials for a step function under different numbers of interpolation nodes and examining instability as the degree increases.

### 3. Boundary Value Problems
Approximating the solution to a second-order differential equation using polynomial-based constructions and finite-difference discretization, then comparing numerical results to the exact solution.

### 4. Eigenvector Analysis
Building a tridiagonal finite-difference matrix, computing its eigenvalues and eigenvectors, and comparing numerical eigenvectors against analytical sine-function modes.

### 5. Error Behavior
Studying how the numerical error changes as the grid size increases, with visual comparisons across multiple values of \(N\).

## Tools
- MATLAB
- numerical linear algebra
- polynomial approximation
- interpolation
- finite differences
- visualization and error plotting

## Files
- `HW5_Real.pdf`: exported code and output from the numerical analysis assignment
- `README.md`: project summary and methodology

## Notes
This repository is organized as a compact numerical methods project and highlights both implementation and numerical behavior, rather than only final answers.
