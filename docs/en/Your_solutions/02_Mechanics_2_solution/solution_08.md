# 8. Work of a Variable Force

## Problem Statement
Given a one-dimensional force $F(x) = -kx$, determine the work done during displacement from $0$ to $x_0$ and relate it to potential energy.

## Step-by-Step Solution

**1. Write the equation of motion:**
Using Newton's Second Law ($F = ma$):
$$-kx = m \frac{d^2x}{dt^2} \implies \frac{d^2x}{dt^2} + \frac{k}{m}x = 0$$
This is the equation for Simple Harmonic Motion (SHM).

**2. Calculate the work done ($W$):**
Work is the integral of force over displacement:
$$W = \int_{0}^{x_0} F(x) dx = \int_{0}^{x_0} (-kx) dx$$
$$W = -k \left[ \frac{1}{2}x^2 \right]_{0}^{x_0} = -\frac{1}{2}kx_0^2$$

**3. Relate to potential energy ($U$):**
Work done by a conservative force is equal to the negative change in potential energy:
$$W = -\Delta U = -(U_{final} - U_{initial})$$
Assuming $U(0) = 0$:
$$-\frac{1}{2}kx_0^2 = -U(x_0) \implies U(x) = \frac{1}{2}kx^2$$

**4. Verify the relationship $F = -dU/dx$:**
$$-\frac{dU}{dx} = -\frac{d}{dx} \left( \frac{1}{2}kx^2 \right) = -kx$$
The result matches the original force.

**5. Interpretation:**
The force $F(x) = -kx$ is a linear restoring force (Hooke's Law), and the potential energy $U(x) = \frac{1}{2}kx^2$ is a parabolic function.
