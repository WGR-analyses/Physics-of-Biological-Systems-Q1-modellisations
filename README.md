# Dynamic Biological Systems: Simulation Projects

This repository hosts a collection of computational projects from a course on modeling dynamic biological systems. The assignments focus on implementing and analyzing models of pattern formation and cytoskeletal dynamics using Python.

## Dependencies

The simulations are built using standard Python scientific computing libraries. To run the code, you will need:
*   `numpy`: For handling numerical arrays and mathematical operations.
*   `matplotlib`: For creating plots and visualizations.
*   `scipy`: Specifically for its powerful ordinary differential equation (ODE) solvers.

You can install these packages using pip:
```bash
pip install numpy matplotlib scipy
```

## Assignment Overview

### Assignment 2: 1D Gray-Scott Reaction-Diffusion Model
This assignment simulates the Gray-Scott model, a classic reaction-diffusion system known for generating complex patterns. The implementation uses the **method of lines** to convert the partial differential equations (PDEs) into a large system of ordinary differential equations (ODEs), which is then solved efficiently using SciPy's `odeint` function.

*   **File:** `Assignement2-code.html`
*   **Key Concepts:** Reaction-diffusion systems, Gray-Scott model, pattern formation, method of lines, solving ODEs.

### Assignment 3: 2D FitzHugh-Nagumo Model
This project models the FitzHugh-Nagumo equations, a simplified representation of neural action potentials, in a 2D space. The simulation is built from scratch using the **finite difference method** to approximate the Laplacian operator for diffusion. The code explicitly handles boundary conditions (Neumann type, where the derivative at the boundary is zero) and steps through time to simulate the evolution of the system.

*   **File:** `Assignement3-code.html`
*   **Key Concepts:** FitzHugh-Nagumo model, excitable media, 2D reaction-diffusion, finite difference method, Laplacian operator, partial differential equations (PDEs).

### Assignment 5/6: Microtubule Dynamic Instability
This assignment implements a stochastic, agent-based model of microtubule dynamics. Each microtubule is an object that can undergo four key processes: growth, catastrophe (switching to decay), rescue (switching back to growth), and nucleation (creation of a new microtubule). The simulation tracks the population of microtubules over time and performs a statistical analysis of their final length and age distributions.

*   **File:** `Assignement5-6-code.html`
*   **Key Concepts:** Microtubule dynamics, dynamic instability, stochastic simulation, agent-based modeling, object-oriented programming, Monte Carlo methods.
