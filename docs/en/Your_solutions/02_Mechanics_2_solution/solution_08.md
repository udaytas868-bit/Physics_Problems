# 8. Work of a Variable Force

## Problem Statement
Given a one-dimensional force described by the equation $F(x) = -kx$, our objective is to:
* Write and solve the equation of motion.
* Calculate the work done during displacement from $0$ to $x_0$.
* Interpret the result in terms of potential energy and verify the force-energy relationship.
* Discuss the graphical representation of $F(x)$ and $U(x)$.

---

## Step-by-Step Solution

### 1. The Equation of Motion
To find the equation of motion, we apply Newton's Second Law, which states that the net force equals mass times acceleration ($F = ma$).
$$m \frac{d^2x}{dt^2} = -kx$$
By rearranging the terms, we get a second-order linear differential equation:
$$\frac{d^2x}{dt^2} + \frac{k}{m}x = 0$$
This is the characteristic equation for **Simple Harmonic Motion (SHM)**. It describes a system where the restoring force is proportional to the displacement, such as a mass on a spring.

### 2. Calculating the Work Done ($W$)
Since the force $F(x)$ depends on the position $x$, it is a variable force. Therefore, we cannot use a simple multiplication ($F \cdot d$). Instead, we must integrate the force over the path from the origin to $x_0$:
$$W = \int_{0}^{x_0} F(x) \, dx$$
Substituting the given force $F(x) = -kx$:
$$W = \int_{0}^{x_0} (-kx) \, dx = -k \left[ \frac{1}{2}x^2 \right]_{0}^{x_0}$$
Evaluating the integral gives the final result for work:
$$W = -\frac{1}{2}kx_0^2$$
*The negative sign indicates that the work is done by the field against the displacement of the particle.*

### 3. Relation to Potential Energy ($U$)
For a conservative force, the work done is equal to the negative change in potential energy ($\Delta U$). We define the potential energy at the equilibrium position ($x=0$) to be zero ($U(0) = 0$).
$$W = -(U(x_0) - U(0))$$
Substituting our calculated work:
$$-\frac{1}{2}kx_0^2 = -U(x_0) \implies U(x) = \frac{1}{2}kx^2$$
This result represents the **Elastic Potential Energy** stored in the system.

### 4. Verification of the Relationship $F = -dU/dx$
We can verify our result by checking if the negative derivative of the potential energy returns the original force function:
$$F = -\frac{dU}{dx} = -\frac{d}{dx} \left( \frac{1}{2}kx^2 \right)$$
Using the power rule for differentiation:
$$F = -\left( \frac{1}{2}k \cdot 2x \right) = -kx$$
The derivation is consistent with the initial force given in the problem statement.

### 5. Graphical Interpretation
* **Force $F(x)$:** This is a linear function with a slope of $-k$. The graph is a straight line passing through the origin, indicating a restoring force.
* **Potential Energy $U(x)$:** This is a quadratic function. The graph is a parabola opening upwards, which shows that energy increases as the particle moves away from $x=0$ in either direction.
