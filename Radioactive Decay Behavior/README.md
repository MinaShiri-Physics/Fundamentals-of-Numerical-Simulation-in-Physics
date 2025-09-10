# Simulation of a Radioactive Decay Problem
- Modeling mutual decay between two types of nuclei, A and B, where A decays into B and vice versa, governed by coupled differential equations with time constant τ=1s.
- Initial conditions: NA(0)=100, NB(0)=0.
- Author: Mina Shiri.

## Numerical Approach
- Euler method for solving the system of ODEs.
- Time step Δt used for discretization (e.g., 0.01 or 0.1 in simulations).
- Demonstrates convergence to steady state where NA(t) ≈ NB(t) as t → ∞.

## Parameters in the Code
- [τ]: Decay time constant (set to 1s).
- NA(0): Initial population of nuclei A (set to 100).
- NB(0): Initial population of nuclei B (set to 0).
- Δt: Time step for Euler integration (tested with values like 0.1 and 0.01).
- t_max: Maximum simulation time (implied to cover convergence, e.g., up to 10s in plots).


## Conclusion
- Both analytical and numerical methods confirm the system reaches equilibrium with NA(t) = NB(t) = 50 at large times.
- Euler method provides accurate approximation with small errors, especially for smaller Δt.
- Stability requires Δt ≤ 1 based on the eigenvalue analysis (λ_max = -2).
- Smaller time steps improve accuracy but increase computational effort.

See [Report.pdf](https://github.com/MinaShiri-Physics/Fundamentals-of-Numerical-Simulation-in-Physics/blob/main/Radioactive%20Decay%20Behavior/Report.pdf) for more details.
