# Particle Decay Simulations (Monte Carlo)

This project implements Monte Carlo simulations of key processes in particle and nuclear physics using Python. It reproduces both relativistic decay kinematics and statistical decay laws through computational methods.

---

## Overview

The project consists of two main parts:

### 1. Relativistic Two-Body Pion Decay
- Simulates:
  - π → μ + ν  
  - π → e + ν  
- Features:
  - Random sampling of pion mass and momentum
  - Isotropic decay in the center-of-momentum frame
  - Lorentz boost to the laboratory frame
- Outputs:
  - Momentum distributions
  - Angular distributions
  - Opening angle between decay products
  - Collimation effects at high energies

---

### 2. Radioactive Decay Simulation
- Models decay as a binomial stochastic process
- Includes:
  - Single-species exponential decay
  - Two-step decay chain: P → Q → R
- Demonstrates:
  - Secular equilibrium
  - Transient equilibrium
  - Non-equilibrium behavior

---

## Key Features

- Vectorized implementation using NumPy
- Large-scale simulations (up to 5 × 10⁵ events)
- Reproducible results with fixed random seed
- Numerical stability safeguards
- Agreement with theoretical predictions

---

## Tech Stack

- Python  
- NumPy  
- Matplotlib  
