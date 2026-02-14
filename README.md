# TP1_FEM_SurrogateWebAPP
1D FEM-based parametric analysis with POD and surrogate modeling,  deployable as a FastAPI web application for real-time design exploration

<p align="center">
  <img src="1D_Elastic.png" width="600">
</p>
---
## Table of Contents
1. Step1 Understanding the Physical Model (1D Elastic Bar Problem) 
2.
3.
4.
5.
---
## How to implement these codes
1. library
- numpy
- 
## **Step1** Understanding the Physical Model (1D Elastic Bar Problem)
### 1-1 Oveview
At this Step1, we analytically solbe the 1D Elastic bar **displacement problem** and define physical parameters. </br>

### 1-2 Overrall Flow 
1. Theory - Derivation of the governing equation and analytical solution.
2. Parameter definition - Defining physical quantities
3. Implementing the analytical solution - Solving the mathematical formula
4. Sensitivity analysis - Investigating how parameters affect displacement

### 1-3 Problem Setup

Consider a one-dimensional elastic bar of length $L$. </br>

- Young’s modulus: $E$ [Pa] (material stiffness)  
- Cross-sectional area: $A$ [m²] (thickness of the bar)  
- Distributed load: $f(x)$ [N/m] (external force per unit length)

##### Boundary Conditions 

- Left end $x = 0$: Fixed (displacement $u = 0$)  
- Right end $x = L$: Free end (stress $\sigma = 0$)  

[back to the title](#tp1_fem_surrogatewebapp)

