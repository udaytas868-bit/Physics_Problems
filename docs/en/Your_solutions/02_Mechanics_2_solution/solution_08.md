# Work of a Variable Force

## Problem

Given a one-dimensional force:

\[
F(x) = -kx
\]

1. Write the equation of motion and solve it.  
2. Calculate the work done during the displacement from \(0\) to \(x_0\).  
3. Interpret the result as potential energy.  
4. Verify the relationship \(F = -\frac{dU}{dx}\).  
5. Draw the graph of \(F(x)\) and \(U(x)\).

---

# 1. Equation of Motion

Using Newton’s Second Law:

\[
F = ma
\]

Substitute the force:

\[
m\frac{d^2x}{dt^2} = -kx
\]

Rearranging:

\[
\frac{d^2x}{dt^2} + \frac{k}{m}x = 0
\]

This is the differential equation of **Simple Harmonic Motion (SHM)**.

The general solution is:

\[
x(t) = A\cos(\omega t + \phi)
\]

where

\[
\omega = \sqrt{\frac{k}{m}}
\]

---

# 2. Work Done by the Force

Work done by a variable force is:

\[
W = \int_{x_i}^{x_f} F(x)\,dx
\]

For displacement from \(0\) to \(x_0\):

\[
W = \int_0^{x_0} (-kx)\,dx
\]

\[
W = -k\int_0^{x_0} x\,dx
\]

\[
W = -k\left[\frac{x^2}{2}\right]_0^{x_0}
\]

\[
W = -\frac{1}{2}kx_0^2
\]

The work is **negative** because the force acts opposite to the displacement.

---

# 3. Potential Energy

For a conservative force:

\[
\Delta U = -W
\]

Assuming \(U(0) = 0\):

\[
U(x_0) = -\left(-\frac{1}{2}kx_0^2\right)
\]

\[
U(x) = \frac{1}{2}kx^2
\]

This is the **potential energy of a spring**.

---

# 4. Verification

Check the relationship:

\[
F = -\frac{dU}{dx}
\]

\[
\frac{dU}{dx} = \frac{d}{dx}\left(\frac{1}{2}kx^2\right)
\]

\[
\frac{dU}{dx} = kx
\]

Therefore:

\[
F = -kx
\]

which matches the original force.

---

# 5. Graphs of \(F(x)\) and \(U(x)\)

- \(F(x) = -kx\) → straight line with negative slope.
- \(U(x) = \frac{1}{2}kx^2\) → upward-opening parabola.

---

## Python Code for Graphs

```python
import numpy as np
import matplotlib.pyplot as plt

k = 1
x = np.linspace(-5,5,100)

F = -k*x
U = 0.5*k*x**2

plt.figure()

plt.plot(x, F, label="F(x) = -kx")
plt.plot(x, U, label="U(x) = 1/2 kx^2")

plt.axhline(0)
plt.axvline(0)

plt.xlabel("x (displacement)")
plt.ylabel("Value")
plt.title("Force and Potential Energy")

plt.legend()
plt.grid(True)

plt.show()
