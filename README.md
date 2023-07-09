# Solving-Maxwells-Equation-by-PINN-Method

This script solves the equation below by using the Physical-Informed- Neural-Network method:

$$
\frac{dj}{dt} + \frac{1}{\tau}j + \frac{\eta D}{2}(j + k_1 * j) = 
\frac{\eta D}{2}(j_0 + k_1 * j_0) + D(t) E_{x0}(0, t)
$$

Assume the time $\tau$ is infinite nd assume the $D(t)$ is a constant denoted by $D$, then we aim to find $j(x, t)$ by solving this equation:

$$
\frac{dj}{dt} + \frac{\eta D}{2}(j + k_1 * j) = 
\frac{\eta D}{2}(j_0 + k_1 * j_0) + D \cdot E_{x0}(0, t)
$$

# Scripts

### 1. PINN - Real Outputs with Constant D

[a relative link](PINN method to solve 4.11 equation - Real Ouput.ipynb)

### 2. PINN - Complex Outputs with Constant D

### 3. PINN - Real Outputs with Time-Dependent D

### 4. PINN - Complex Outputs with Time-Dependent D
