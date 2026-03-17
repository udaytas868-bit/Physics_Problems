# Problem 10: 3D Kinematics

## Solution
$\vec{r}(t) = (a \cos(\omega t), b \sin(\omega t), bt)$

### (a) Trajectory
The $x$ and $y$ components satisfy $\frac{x^2}{a^2} + \frac{y^2}{b^2} = 1$, which is an ellipse. The $z$ component grows linearly. This defines an **elliptical helix**.

### (b) Path Length
$v(t) = \frac{d\vec{r}}{dt} = (-a\omega \sin\omega t, b\omega \cos\omega t, b)$
Length $s = \int_{0}^{t_0} \sqrt{(-a\omega \sin\omega t)^2 + (b\omega \cos\omega t)^2 + b^2} dt$
If $a=b$, $s = \int_{0}^{t_0} \sqrt{b^2\omega^2 + b^2} dt = t_0 \sqrt{b^2(\omega^2+1)}$.
