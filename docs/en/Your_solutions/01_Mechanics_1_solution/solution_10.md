# 10. Kinematics – Solution

The motion of point \( M \) is given by:

\[
\vec{r}(t) = \big(a\cos(\omega t),\; b\sin(\omega t),\; bt\big)
\]

where \( a, b, \omega > 0 \).

---

## a) Equation of the Trajectory

From the parametric equations:

\[
x = a\cos(\omega t), \quad y = b\sin(\omega t)
\]

we obtain:

\[
\cos(\omega t) = \frac{x}{a}, \quad \sin(\omega t) = \frac{y}{b}
\]

Using the identity:

\[
\cos^2(\omega t) + \sin^2(\omega t) = 1
\]

we get:

\[
\frac{x^2}{a^2} + \frac{y^2}{b^2} = 1
\]

Also:

\[
z = bt \Rightarrow t = \frac{z}{b}
\]

### Result:

The trajectory is an **elliptical helix** along the \( z \)-axis.

---

## b) Path Length

The arc length is:

\[
s = \int_0^{t_0} \left|\vec{r}'(t)\right| dt
\]

Derivative:

\[
\vec{r}'(t) = (-a\omega \sin(\omega t),\; b\omega \cos(\omega t),\; b)
\]

Magnitude:

\[
|\vec{r}'(t)| = \sqrt{a^2\omega^2 \sin^2(\omega t) + b^2\omega^2 \cos^2(\omega t) + b^2}
\]

\[
= \sqrt{\omega^2(a^2 \sin^2(\omega t) + b^2 \cos^2(\omega t)) + b^2}
\]

Thus:

\[
s = \int_0^{t_0} \sqrt{\omega^2(a^2 \sin^2(\omega t) + b^2 \cos^2(\omega t)) + b^2}\, dt
\]

> Note: This integral generally does not have a closed-form solution and is expressed using elliptic integrals.

---

## c) Plotting the Trajectory (Python)

```python
import numpy as np
import matplotlib.pyplot as plt

# constants
a = 2
b = 1
omega = 2

t = np.linspace(0, 10, 1000)

x = a * np.cos(omega * t)
y = b * np.sin(omega * t)
z = b * t

fig = plt.figure()
ax = fig.add_subplot(projection='3d')

ax.plot(x, y, z)
ax.set_xlabel('X')
ax.set_ylabel('Y')
ax.set_zlabel('Z')

plt.show()
