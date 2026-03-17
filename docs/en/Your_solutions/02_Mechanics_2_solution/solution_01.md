## Problem 1: Projectile Motion
**Given:** $v_0 = 100 \text{ m/s}$, $\theta = 37^\circ$, $g = 9.8 \text{ m/s}^2$

### 1. Differential Equations of Motion
- Horizontal: $a_x = \frac{d^2x}{dt^2} = 0$
- Vertical: $a_y = \frac{d^2y}{dt^2} = -g$

### 2. Time of Flight ($t_{flight}$)
The vertical position is $y(t) = (v_0 \sin \theta)t - \frac{1}{2}gt^2$. Setting $y=0$:
$t_{flight} = \frac{2v_0 \sin \theta}{g} = \frac{2 \cdot 100 \cdot 0.6}{9.8} \approx 12.24 \text{ s}$

### 3. Maximum Height ($H_{max}$)
$H_{max} = \frac{(v_0 \sin \theta)^2}{2g} = \frac{(100 \cdot 0.6)^2}{2 \cdot 9.8} = \frac{3600}{19.6} \approx 183.67 \text{ m}$

### 4. Range ($R$)
$R = \frac{v_0^2 \sin(2\theta)}{g} = \frac{100^2 \cdot \sin(74^\circ)}{9.8} \approx \frac{10000 \cdot 0.96}{9.8} \approx 979.59 \text{ m}$
