## Ising Model and Monte Carlo Simulation
This project simulates the 2D Ising model using Monte Carlo methods to study magnetic properties of a lattice with spins (±1) interacting up to third neighbors.
### System
- 2D lattice with spins s_i = ±1, periodic boundaries.
- Constants: J1/k = 1, J2/k = 0.5, J3/k = 0.2 (k = 1).

### Simulation
- Monte Carlo with Metropolis: Flips spins if ΔE < [0 or exp(-ΔE/T)].
- Lattice sizes: 10x10 to 100x100; temps 1 to 10.
- Steps: 10 to 1000; includes time/ensemble averaging.

### Results
- Energy rises, magnetization drops with temperature; Curie point ~5-6.
- Larger lattices smooth fluctuations.
- J2, J3 lower energy, shift Curie point higher.
- Code: [Link](https://github.com/MinaShiri-Physics/Fundamentals-of-Numerical-Simulation-in-Physics/blob/main/Ising%20Model%20Simulation/Code.ipynb)

See [Report.pdf](https://github.com/MinaShiri-Physics/Fundamentals-of-Numerical-Simulation-in-Physics/blob/main/Ising%20Model%20Simulation/Report.pdf) for details.
