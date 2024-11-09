# SDE-Solver

This repository contains a Jupyter notebook that implements a solver for Stochastic Differential Equations (SDEs) using the Euler-Maruyama scheme. The Euler-Maruyama method is a simple and widely used numerical method for solving SDEs, especially when dealing with stochastic processes.

The notebook demonstrates how to:
1) Define and solve SDEs.
2) Visualize sample paths of the solution.
3) Estimate the mean and covariance of the process at different times.

This code simulate some Ito SDE's given by

$$dX_t = \mu(t,X_t,W_t) dt + \sigma(t,X_t,W_t)dW_t$$

using Euler–Maruyama method 

$$X_{t+\Delta t} = X_{t}+\mu(t,X_t,W_t)\Delta t + \sigma(t,X_t,W_t)\sqrt{\Delta t}Z$$

wher $Z \sim \mathcal{N}(0,1)$ is a gaussian variable.

