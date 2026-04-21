# 3. Superposition Principle and Standing Waves

## Problem Statement
We are given two waves traveling in opposite directions described by the following equations:
* $y_1(t,x) = A \sin(\omega t - kx)$
* $y_2(t,x) = A \sin(\omega t + kx)$

Our goal is to determine the resulting wave equation using the **Superposition Principle** and identify the positions of the **Nodes**.

---

## Step-by-Step Solution

### 1. Applying the Superposition Principle
According to the principle of superposition, the resulting displacement $y_{res}$ is the algebraic sum of the individual displacements:
$$y_{res}(t,x) = y_1 + y_2 = A \sin(\omega t - kx) + A \sin(\omega t + kx)$$

To simplify this, we use the trigonometric identity for the sum of sines:
$$\sin(\alpha) + \sin(\beta) = 2 \sin\left(\frac{\alpha + \beta}{2}\right) \cos\left(\frac{\alpha - \beta}{2}\right)$$

### 2. Deriving the Standing Wave Equation
Let $\alpha = \omega t + kx$ and $\beta = \omega t - kx$:
* $\frac{\alpha + \beta}{2} = \frac{(\omega t + kx) + (\omega t - kx)}{2} = \omega t$
* $\frac{\alpha - \beta}{2} = \frac{(\omega t + kx) - (\omega t - kx)}{2} = kx$

Substituting these into the identity:
$$y_{res}(t,x) = 2A \sin(\omega t) \cos(kx)$$

**Conclusion:** The resulting equation describes a **standing wave** where the amplitude $2A \cos(kx)$ depends on the position $x$, and it oscillates in time with $\sin(\omega t)$.

---

### 3. Identifying the Positions of the Nodes
Nodes are points where the displacement is always zero ($y_{res} = 0$). This happens when the spatial part of the equation is zero:
$$\cos(kx) = 0$$

The cosine function is zero at odd multiples of $\pi/2$:
$$kx = (2n + 1)\frac{\pi}{2} \quad \text{where } n = 0, 1, 2, \dots$$

Since $k = \frac{2\pi}{\lambda}$, we can solve for $x$:
$$\left(\frac{2\pi}{\lambda}\right)x = (2n + 1)\frac{\pi}{2}$$
$$x = \frac{(2n + 1)\lambda}{4}$$

**Result:** The nodes are located at:
* $x = \frac{\lambda}{4}, \frac{3\lambda}{4}, \frac{5\lambda}{4}, \dots$

---

## Discussion
In this resulting wave, the energy does not travel through the medium but is stored in the oscillations. The points between the nodes that reach maximum displacement are called **Antinodes**, which occur when $\cos(kx) = \pm 1$.
