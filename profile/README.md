# Computational Mesoscale Materials Science

This project is supported as part of the [Computational Materials Sciences Program](https://www.greencarcongress.com/2019/06/20190613-doe.html) funded by the US Department of Energy, Office of Science, Basic Energy Sciences, under Award Number DE-SC0020145 (DOE Program Manager: Matthias Graf, Matthias.Graf@science.doe.gov)

## Q-POP

A primary objective of this project is to create a software package (Q-POP, Quantum Phase-field Open-source Package) that facilitates computationally efficient phase-field modeling of quantum materials. Q-POP empowers researchers to investigate quantum materials and phase transitions—including superconductivity, metal-insulator transitions, and strongly-correlated materials—through the application of the phase-field method.

Many of the codes below are in its initial releasing phase, and we are integrating other tools and codes that we have developed into Q-POP, ensuring a seamless and user-friendly experience for all users.

### Pre simulation tools

1. Q-POP-HTP: high-throughput simulation jobs generator
1. Q-POP-Thermo: to calculate the equilibrium temperature-strain phase
2. Q-POP-BoltzTraP2Y: a high-throughput first-principles calculation software to provide thermodynamic and kinetic input data for phase-field simulations

### Main modules

The main modules are within one single repository called Q-POP-modules, because they are sharing common utilities and solvers from the same core library.

1. Q-POP-IMT: to simulate metal-insulator transition
2. Q-POP-FerroDyn: to model charge-elasticity-photon coupled dynamics
3. Q-POP-SuperCon: to model superconducting phase transition and quantum hall effect.

### Post simulation tools

1. Q-POP-Diffraction: to compute diffration patterns of phase-field simulated microstructures
2. Q-POP-PyVecAnalysis: to automate identification of topological structures
3. Q-POP-SHAARP: analytical and numerical modeling of optical second harmonic generation in anisotropic crystals
