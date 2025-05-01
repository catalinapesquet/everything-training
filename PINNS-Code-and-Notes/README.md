# PINNS-Code-and-Notes (Physics-informed neural networks)

This repository contains Jupyter notebooks showcasing the implementation of Physics-Informed Neural Networks (PINNs) to solve Partial Differential Equations (PDEs). The notebooks demonstrate the application of PINNs to the Diffusion Equation and Burgers' Equation.

## Diffusion Equation (Diffusion_Equation_PINN.ipynb):
This notebook implements a PINN to solve the Diffusion Equation, a fundamental PDE used in modeling heat transfer and particle diffusion in physics and engineering.
The solution is computed by leveraging automatic differentiation for computing gradients of the neural network output, which represents the solution u(x,t).

## Burgers' Equation (Burgers_Equation_PINN.ipynb):

This notebook focuses on solving the Burgers' Equation, a nonlinear PDE used in fluid mechanics, traffic flow, and gas dynamics.
The PINN learns the solution u(x,t) and simultaneously predicts the parameters λ1 (convection) and λ2 (diffusion) involved in the equation.


