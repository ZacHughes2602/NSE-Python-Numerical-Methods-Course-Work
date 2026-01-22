# NSE-Python-Numerical-Methods-Course-Work

![Reactor Core Visualization](Reactor_Core.png)
*Figure 1: Generated TRIGA-like reactor core geometry showing fuel pins, control rods, and graphite reflectors.*

This repository contains a collection of numerical methods and reactor physics simulations developed using Python. The projects focus on implementing core mathematical algorithms from scratch to solve neutron transport, linear algebra, and reactor geometry problems.

## Technologies
* **Language:** Python
* **Libraries:** NumPy, Matplotlib, SciPy
* **Concepts:** Monte Carlo Simulation, Numerical Integration, Linear Algebra, Constructive Solid Geometry (CSG)

##Project Modules

### 1. Numerical Linear Algebra Solvers (`HW4`)
* **Algorithm:** Implementation of Gaussian Elimination with Back-Substitution from first principles.
* **Validation:** Solves $Ax=b$ for dense systems and analyzes residual error growth for ill-conditioned matrices (e.g., $N=16$ Hilbert-like matrices) to demonstrate numerical instability.

### 2. Numerical Integration & Interpolation (`HW6`)
* **Algorithms:** Trapezoidal Rule, Simpson's 1/3 Rule, and Romberg Integration.
* **Application:** Integration of Bessel functions ($J_0$) and Lagrange Polynomial interpolation for scatter data points.
* **Results:** Comparative error analysis showing $O(h^2)$ vs $O(h^4)$ convergence rates.

### 3. Reactor Core Visualization (`HW3`)
* **Visualization:** Programmatic generation of a TRIGA-like reactor core lattice.
* **Logic:** algorithmically places fuel pins, control rods (B4C), and graphite reflectors in concentric rings.

## How to Run
These projects are presented as Jupyter Notebooks. To run them:
1. Clone the repo:
   ```bash
   git clone [https://github.com/your-username/Computational-Nuclear-Engineering.git](https://github.com/your-username/Computational-Nuclear-Engineering.git)
