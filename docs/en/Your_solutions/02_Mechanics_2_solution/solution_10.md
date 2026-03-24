# 10. Force Field and Power: Step-by-Step Analysis

## Problem Statement
In a force field, a particle with mass **$m = 0.5 \text{ kg}$** moves according to the following parametric equations of motion:
* $x(t) = 5t^2 - t$
* $y(t) = 2t^3$
* $z(t) = -3t + 2$

We need to find the time dependence of the particle's velocity, momentum, acceleration, force, and power.

---

## Step 1: Particle's Velocity ($\vec{v}$)
Velocity is defined as the first derivative of the position vector $\vec{r}(t)$ with respect to time ($t$):
$$\vec{v}(t) = \frac{d\vec{r}}{dt} = \left( \frac{dx}{dt}, \frac{dy}{dt}, \frac{dz}{dt} \right)$$

* $v_x = \frac{d}{dt}(5t^2 - t) = 10t - 1$
* $v_y = \frac{d}{dt}(2t^3) = 6t^2$
* $v_z = \frac{d}{dt}(-3t + 2) = -3$

**Result:** $\vec{v}(t) = (10t - 1)\hat{i} + (6t^2)\hat{j} - 3\hat{k}$

---

## Step 2: Particle's Momentum ($\vec{p}$)
Momentum is the product of the particle's mass ($m$) and its instantaneous velocity ($\vec{v}$):
$$\vec{p}(t) = m \cdot \vec{v}(t)$$
Using $m = 0.5 \text{ kg}$:
* $p_x = 0.5 \cdot (10t - 1) = 5t - 0.5$
* $p_y = 0.5 \cdot (6t^2) = 3t^2$
* $p_z = 0.5 \cdot (-3) = -1.5$

**Result:** $\vec{p}(t) = (5t - 0.5)\hat{i} + (3t^2)\hat{j} - 1.5\hat{k}$

---

## Step 3: Particle's Acceleration ($\vec{a}$)
Acceleration is the derivative of the velocity vector with respect to time:
$$\vec{a}(t) = \frac{d\vec{v}}{dt}$$

* $a_x = \frac{d}{dt}(10t - 1) = 10$
* $a_y = \frac{d}{dt}(6t^2) = 12t$
* $a_z = \frac{d}{dt}(-3) = 0$

**Result:** $\vec{a}(t) = 10\hat{i} + 12t\hat{j}$

---

## Step 4: Force Acting on the Particle ($\vec{F}$)
According to Newton's Second Law, the force is the product of mass and acceleration:
$$\vec{F}(t) = m \cdot \vec{a}(t)$$
Using $m = 0.5 \text{ kg}$:
* $F_x = 0.5 \cdot 10 = 5$
* $F_y = 0.5 \cdot 12t = 6t$
* $F_z = 0.5 \cdot 0 = 0$

**Result:** $\vec{F}(t) = 5\hat{i} + 6t\hat{j}$ (Units: Newtons)

---

## Step 5: Power Transferred by the Field ($P$)
Instantaneous power is calculated by the dot product of the force vector and the velocity vector:
$$P(t) = \vec{F}(t) \cdot \vec{v}(t) = (F_x v_x) + (F_y v_y) + (F_z v_z)$$

* $P(t) = [5 \cdot (10t - 1)] + [6t \cdot (6t^2)] + [0 \cdot (-3)]$
* $P(t) = (50t - 5) + (36t^3) + 0$

**Final Result:** $P(t) = 36t^3 + 50t - 5$ (Units: Watts)
