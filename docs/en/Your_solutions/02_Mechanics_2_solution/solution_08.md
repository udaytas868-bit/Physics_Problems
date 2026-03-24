# 8. Work of a Variable Force: Step-by-Step Analysis

## Problem Overview
In this problem, we analyze a particle subject to a linear restoring force, commonly known as **Hooke's Law**. The primary goal is to derive the work done by the field and understand its relationship with potential energy.

---

## Step 1: Equation of Motion
Based on Newton's Second Law ($F = ma$), we define the force acting on the mass $m$:
$$F(x) = -kx$$
Substituting this into the acceleration formula:
$$m \frac{d^2x}{dt^2} = -kx \implies \frac{d^2x}{dt^2} + \frac{k}{m}x = 0$$

> **Student Note:** This is the standard differential equation for **Simple Harmonic Motion (SHM)**. It shows that the acceleration is always proportional to the displacement but in the opposite direction.

---

## Step 2: Calculation of Work Done ($W$)
Since the force is not constant, we cannot simply multiply force by distance. We must calculate the work as an integral from an initial position (equilibrium) to a final position $x_0$:
$$W = \int_{0}^{x_0} F(x) \, dx$$

Substituting the force function:
$$W = \int_{0}^{x_0} (-kx) \, dx = -k \left[ \frac{1}{2}x^2 \right]_{0}^{x_0}$$
**Result:** $W = -\frac{1}{2}kx_0^2$

*Note: The work is negative because the force acts against the direction of the displacement.*

---

## Step 3: Potential Energy Derivation
In physics, the change in potential energy is defined as the negative of the work done by a conservative force:
$$\Delta U = -W$$
Assuming $U(0) = 0$ at the equilibrium point:
$$U(x_0) - 0 = -(-\frac{1}{2}kx_0^2)$$
**Result:** $U(x) = \frac{1}{2}kx^2$

---

## Step 4: Verification ($F = -dU/dx$)
To confirm our results are consistent, we check if the negative gradient of the potential energy gives us the original force:
$$-\frac{dU}{dx} = -\frac{d}{dx} \left( \frac{1}{2}kx^2 \right) = -kx$$
**Conclusion:** The result matches the initial force $F(x)$, verifying our derivation.

---

## Step 5: Interpretation and Visualization
If we were to plot these functions:
1. **Force $F(x)$**: This would be a straight line with a negative slope ($k$). It always pulls the particle back to $x=0$.
2. **Potential Energy $U(x)$**: This is a parabola. It shows that energy is stored regardless of whether the displacement is positive or negative (stretching or compressing).

