# Problem 2: Range Optimization

## Necessary formulas
Range $R$ is given by:
$$R(\theta) = \frac{v_0^2 \sin(2\theta)}{g}$$

---

## Analytical Proof
To find the maximum range, we take the derivative of $R$ with respect to $\theta$ and set it to zero:
$$\frac{dR}{d\theta} = \frac{v_0^2}{g} \frac{d}{d\theta}(\sin(2\theta)) = \frac{v_0^2}{g} \cdot 2\cos(2\theta)$$
Setting $\frac{dR}{d\theta} = 0$:
$$2\cos(2\theta) = 0 \implies \cos(2\theta) = 0$$
$$2\theta = 90^\circ \implies \theta = 45^\circ$$
Thus, for any given initial velocity, the maximum range is achieved at a $45^\circ$ launch angle.
