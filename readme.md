# PINN Tutorial

## Overview

This repository contains a minimal implementation of **Physics-Informed Neural Networks** (PINNs) in PyTorch. PINNs combine neural networks with physics-based constraints, making them particularly useful for solving problems described by ordinary/partial differential equations.

## Files


1. **DataDrivenSolutionODE.ipynb**
   - Demonstrates the application of PINNs for finding solutions to ordinary differential equations (ODEs).
2. **DataDrivenDiscoveryODE.ipynb**
   - This notebook explores the data-driven discovery of solutions to ordinary differential equations (ODEs) using PINNs.
3. **DataDrivenSolutionPDE.ipynb**
   - Extends the application of PINNs to partial differential equations (PDEs).
4. **LaneEmdenDifferentialEquation.ipynb**
   - Solving the well-known Lane-Emden differential equation using PINNs.
5. **ODE-NAS.ipynb**
   - Running a Neural Architecture Search (NAS) on PINNs for solving an ODE.
6. **PDE-LBFGS.ipynb**
   - Using Quasi-Newton LBFGS algorithm for faster convergence.
7. **PDE-LBFGS-CUDA.ipynb**
   - Add CUDA support to speedup the learning process.

## Getting Started

To run these notebooks, ensure you have Python and PyTorch (preferably with CUDA support) installed. You can install the required packages using:

```bash
pip install -r requirements.txt
```
Clone the repository:
```bash
git clone https://github.com/your-username/PINN-tutorial.git cd PINN-tutorial
```
Open the desired notebook using Jupyter:
```bash
jupyter notebook DataDrivenDiscoveryODE.ipynb
```
Feel free to explore and modify the code to suit your needs.

## References
For a deeper understanding of Physics-Informed Neural Networks and their applications, refer to the following resources:
- [A tutorial on PINNs by Alireza Afzal Aghaei](https://slides.com/alirezaafzalaghaei/tensorflow)
- [A neural network approach for solving nonlinear differential equations of Lane–Emden type](https://link.springer.com/article/10.1007/s00366-023-01836-5)
-   [Physics-Informed Neural Networks: A Deep Learning Framework for Solving Forward and Inverse Problems Involving Nonlinear Partial Differential Equations](https://arxiv.org/abs/1711.10561)

## License

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE](https://chat.openai.com/c/LICENSE) file for details.
