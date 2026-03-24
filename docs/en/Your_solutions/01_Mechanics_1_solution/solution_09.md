# Mechanics I: Comprehensive Problem Solutions

## 1. Projectile Motion
**Step 1: Velocity Decomposition** We split the initial velocity $v_0 = 100 \text{ m/s}$ into horizontal ($x$) and vertical ($y$) components using $\theta = 37^\circ$:
* $v_{0x} = v_0 \cos(37^\circ) = 100 \cdot 0.8 = 80 \text{ m/s}$
* $v_{0y} = v_0 \sin(37^\circ) = 100 \cdot 0.6 = 60 \text{ m/s}$

**Step 2: Differential Equations of Motion** Applying Newton's Second Law ($F=ma$) with no air resistance:
* Horizontal: $m \frac{d^2x}{dt^2} = 0 \implies \frac{d^2x}{dt^2} = 0$
* Vertical: $m \frac{d^2y}{dt^2} = -mg \implies \frac{d^2y}{dt^2} = -g$

**Step 3: Calculations** * **Time of Flight ($t_f$):** Found by setting $y(t) = (v_{0y})t - \frac{1}{2}gt^2 = 0$.  
  $t_f = \frac{2v_{0y}}{g} = \frac{120}{9.8} \approx 12.24 \text{ s}$
* **Maximum Height ($H$):** Found when $v_y = 0$.  
  $H = \frac{v_{0y}^2}{2g} = \frac{3600}{19.6} \approx 183.7 \text{ m}$
* **Range ($R$):** The total horizontal distance.  
  $R = v_{0x} \cdot t_f = 80 \cdot 12.24 \approx 979.2 \text{ m}$

---

## 2. Range Optimization
**Step 1: The Analytical Function** The range is given by $R(\theta) = \frac{v_0^2 \sin(2\theta)}{g}$.

**Step 2: Differentiation for Maximum** To find the local maximum, we take the derivative with respect to the launch angle $\theta$:  
$\frac{dR}{d\theta} = \frac{v_0^2}{g} \cdot \frac{d}{d\theta}(\sin 2\theta) = \frac{v_0^2}{g} \cdot (2 \cos 2\theta)$

**Step 3: Solving the Condition** Setting the derivative to zero:  
$2 \cos 2\theta = 0 \implies 2\theta = 90^\circ \implies \theta = 45^\circ$.  
Thus, the maximum range is always achieved at $45^\circ$.

---

## 3. Path Intersection
**Step 1: Coordinate Comparison** Alice: $A(t) = (2+t, 8-3t)$  
Bob: $B(t) = (2t-1, 2t+2)$  
Setting $x_A = x_B$: $2+t = 2t-1 \implies t = 3$.

**Step 2: Verification of $y$ at $t=3$** * Alice at $t=3$: $y_A = 8 - 3(3) = -1$
* Bob at $t=3$: $y_B = 2(3) + 2 = 8$  
Since $-1 \neq 8$, their paths cross the same $x$-coordinate at $t=3$, but they are at different heights. They **do not collide**.

**Step 3: Minimum Distance** To find the minimum distance, we minimize $d^2(t) = (x_A-x_B)^2 + (y_A-y_B)^2$. Solving $d'(t)=0$ gives the time of closest approach.

---

## 4. Vector Calculus
**Step 1: Velocity Vector ($\vec{v}$)** $\vec{v}(t) = \frac{d\vec{r}}{dt} = \frac{d}{dt} \left( 3t^2 \hat{i} + (5t - 8t^2) \hat{j} \right)$  
$\vec{v}(t) = (6t) \hat{i} + (5 - 16t) \hat{j}$

**Step 2: Acceleration Vector ($\vec{a}$)** $\vec{a}(t) = \frac{d\vec{v}}{dt} = \frac{d}{dt} \left( 6t \hat{i} + (5 - 16t) \hat{j} \right)$  
$\vec{a}(t) = 6 \hat{i} - 16 \hat{j}$

---

## 5. Relative Velocity
**Step 1: Finding the Heading Angle** To travel directly North, the boat's horizontal velocity must cancel the river's eastward flow ($2 \text{ m/s}$):  
$5 \sin \theta = 2 \implies \sin \theta = 0.4 \implies \theta \approx 23.6^\circ$ **West of North**.

**Step 2: Calculating Crossing Time** The effective velocity North is $v_y = 5 \cos(23.6^\circ) \approx 4.58 \text{ m/s}$.  
$t = \frac{\text{Distance}}{\text{Velocity}} = \frac{200 \text{ m}}{4.58 \text{ m/s}} \approx 43.7 \text{ s}$.

---

## 6. Variable Velocity
**Step 1: Acceleration at $t=3$** $a(t) = \frac{dv}{dt} = 2t + 2$.  
At $t=3$: $a(3) = 2(3) + 2 = 8 \text{ m/s}^2$.

**Step 2: Position at $t=3$** $x(t) = \int (t^2 + 2t - 5) dt = \frac{1}{3}t^3 + t^2 - 5t + C$.  
Using $x(0) = 4$, we find $C = 4$.  
$x(3) = \frac{1}{3}(27) + 9 - 15 + 4 = 9 + 9 - 15 + 4 = 7 \text{ m}$.

---

## 7. Path Equation Analysis
**Step 1: Elimination of Parameter $t$** From $x = 2t^2$, we have $t^2 = \frac{x}{2} \implies t = \sqrt{\frac{x}{2}}$.  
Substitute into $y$: $y = 3 \left( \sqrt{\frac{x}{2}} \right)^3 = 3 \left( \frac{x}{2} \right)^{1.5}$.

**Step 2: Acceleration** $\vec{v}(t) = (4t, 9t^2)$, $\vec{a}(t) = (4, 18t)$.  
The acceleration is **not constant** because it depends on time $t$.

---

## 8. Circular Motion
**Step 1: Constants** Earth radius $R = 6,378,000 \text{ m}$.  
Period $T = 24 \text{ hours} = 86,400 \text{ s}$.  
Angular velocity $\omega = \frac{2\pi}{T} \approx 7.27 \times 10^{-5} \text{ rad/s}$.

**Step 2: Centripetal Acceleration** $a_c = \omega^2 R = (7.27 \times 10^{-5})^2 \cdot 6,378,000 \approx 0.034 \text{ m/s}^2$.

---

## 9. Momentum Comparison
**Step 1: Standardizing Units (SI)** * Fly: $m = 2 \text{ g} = 0.002 \text{ kg}$, $v = 10 \text{ m/s}$
* Tennis Ball: $m = 60 \text{ g} = 0.06 \text{ kg}$, $v = 1 \text{ m/s}$

**Step 2: Calculation ($p = mv$)** * $p_{\text{fly}} = 0.002 \cdot 10 = 0.02 \text{ kg}\cdot\text{m/s}$
* $p_{\text{ball}} = 0.06 \cdot 1 = 0.06 \text{ kg}\cdot\text{m/s}$  
**Conclusion:** The tennis ball has a significantly greater momentum.

---

## 10. 3D Kinematics
**a) Trajectory:** Combining $x$ and $y$ gives $(x/a)^2 + (y/b)^2 = 1$, which is an ellipse. Since $z$ increases linearly with time ($z=bt$), the trajectory is an **elliptical helix**.  
**b) Path Length:** $s = \int_0^{t_0} \sqrt{(\frac{dx}{dt})^2 + (\frac{dy}{dt})^2 + (\frac{dz}{dt})^2} dt$  
$s = \int_0^{t_0} \sqrt{(-a\omega \sin \omega t)^2 + (b\omega \cos \omega t)^2 + b^2} dt$.
