
## Quantum Mechanics Simulation

A spectral method is a procedure for calculating the value of an observable which depends on the spectrum of the system.  Spectral methods are used in fields of physics, chemistry, and electronics to solve a differential or integral equation and determine the value of a function.  Since they solve the problem via analytic expression they are especially useful when the analytical solution is too complex, too hard to obtain, or not at all possible.  In such cases the spectral method offers much of the speed of iterative methods at the cost of some simplicity.

## Spectral Solver for Schrodinger-Poisson Quantum System

Simulate the Schrodinger-Poisson system with the Spectral Method

```
python quantum_spectral.py
```

The simulation simply places a few random Gaussian-shaped overdensities in a periodic 2D box and lets it evolve under self-gravity. The structures are attracted towards each other by gravity, and exhibit wavelike fluctuations.

Schrodinger-Poisson solver to visualize the simulation in real time
![Simulation](.assets/quantumspectral.png)
