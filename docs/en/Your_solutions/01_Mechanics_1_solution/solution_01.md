# Problem 1: Projectile Motion

## Necessary definitions and formulas
1. **Initial Velocity Components:**
   $v_{0x} = v_0 \cos\theta, \quad v_{0y} = v_0 \sin\theta$
2. **Equations of Motion:**
   $x(t) = v_{0x}t$
   $y(t) = v_{0y}t - \frac{1}{2}gt^2$

---

## Solution

Given: $v_0 = 100 \text{ m/s}$, $\theta = 37^\circ$, $g \approx 9.8 \text{ m/s}^2$.
Using $\sin(37^\circ) \approx 0.6$ and $\cos(37^\circ) \approx 0.8$:

### (a) Differential equations of motion
* **Horizontal:** $m \frac{d^2x}{dt^2} = 0 \implies \ddot{x} = 0$
* **Vertical:** $m \frac{d^2y}{dt^2} = -mg \implies \ddot{y} = -g$

### (b) Time of flight ($t_{fly}$)
Setting $y(t) = 0$:
$$t_{fly} = \frac{2v_0 \sin\theta}{g} = \frac{2 \cdot 100 \cdot 0.6}{9.8} \approx 12.24 \text{ s}$$

### (c) Maximum height ($H_{max}$)
$$H_{max} = \frac{(v_0 \sin\theta)^2}{2g} = \frac{(60)^2}{19.6} \approx 183.67 \text{ m}$$

### (d) Range ($R$)
$$R = \frac{v_0^2 \sin(2\theta)}{g} = \frac{10000 \cdot 0.96}{9.8} \approx 979.59 \text{ m}$$
