# Laplace Equation Numerical Solver
- Solving Laplace's equation (∇²V = 0) with mixed boundary conditions in a 2x2 domain.
- Author: Mina Shiri.

## Numerical Approach
- Finite difference method with Gauss-Seidel iteration.
- Discretize domain into N×N grid (h=2/(N-1)).

## Parameters in the Code
The code defines and uses the following key parameters for solving the Laplace equation numerically:
- **L**: Length of the square domain
- **grid_sizes**: Size o the grid
- **dx**: Grid spacing, calculated as L / (grid_size - 1)
- **max_iterations:** Maximum number of iterations for convergence (set to 10000)
- **tolerance:** Convergence threshold for the potential update (set to 1e-6)
- **start_time:** Start time for timing the iteration 
- **elapsed_time:** Time taken for convergence

## Conclusion
- Finer grids enhance accuracy but raise computational cost.
- Highlights balance in mesh size for efficiency in physics/engineering problems.
- You can modify grid_sizes or ε for experiments.

See [Report.pdf](https://github.com/MinaShiri-Physics/Fundamentals-of-Numerical-Simulation-in-Physics/blob/main/Laplace%20Equation/Report.pdf) for more details.
