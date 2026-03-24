# 8. Work of a Variable Force: Step-by-Step Analysis

## Problem Statement
Given a one-dimensional force acting on a particle:
$$F(x) = -kx$$
where $k$ is a positive constant (Hooke's Law). We need to analyze the equation of motion, calculate the work done, and interpret the relationship between force and potential energy.

---

## Step 1: Equation of Motion and Its Solution
According to Newton's Second Law ($F = ma$), the equation of motion for a mass $m$ is:
$$m \frac{d^2x}{dt^2} = -kx \implies \frac{d^2x}{dt^2} + \frac{k}{m}x = 0$$

This is a **Simple Harmonic Motion (SHM)** differential equation. Defining $\omega^2 = \frac{k}{m}$, the general solution is:
$$x(t) = A \cos(\omega t + \phi)$$
where $A$ is the amplitude and $\phi$ is the phase constant.

---

## Step 2: Calculation of Work Done
Work done $W$ by a variable force during displacement from $0$ to $x_0$ is the integral of the force over the path:
$$W = \int_{0}^{x_0} F(x) \, dx$$

Substituting $F(x) = -kx$:
$$W = \int_{0}^{x_0} (-kx) \, dx = -k \left[ \frac{1}{2}x^2 \right]_{0}^{x_0}$$
**Result:** $W = -\frac{1}{2}kx_0^2$

---

## Step 3: Interpretation as Potential Energy
In a conservative field, the work done by the field is equal to the negative change in potential energy ($W = -\Delta U$). 
Since the particle starts from $x=0$ (where we define $U(0) = 0$):
$$\Delta U = U(x_0) - U(0) = -W$$
$$U(x_0) = -(-\frac{1}{2}kx_0^2)$$
**Result:** $U(x) = \frac{1}{2}kx^2$ (This is the Elastic Potential Energy).

---

## Step 4: Verification of the Relationship $F = -\frac{dU}{dx}$
To verify, we take the negative gradient of the potential energy derived in Step 3:
$$-\frac{dU}{dx} = -\frac{d}{dx} \left( \frac{1}{2}kx^2 \right)$$
$$-\frac{dU}{dx} = -\left( \frac{1}{2}k \cdot 2x \right) = -kx$$
**Verification:** Since $-kx$ is the original force $F(x)$, the relationship is confirmed.

---

## Step 5: Graphical Representation
The functions to be graphed are:
1. **Force $F(x) = -kx$:** A linear function with a negative slope passing through the origin. It represents a restoring force.
2. **Potential Energy $U(x) = \frac{1}{2}kx^2$:** A parabola opening upwards with its vertex at the origin.

> **Note:** The force is always directed towards the equilibrium position ($x=0$), while the potential energy increases quadratically as the particle moves away from the origin.
