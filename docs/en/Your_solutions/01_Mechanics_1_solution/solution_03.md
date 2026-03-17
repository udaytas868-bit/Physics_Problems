# Problem 3: Path Intersection

## Given Paths
Alice: $A(t) = (2+t, 8-3t)$
Bob: $B(t) = (2t-1, 2t+2)$

---

## Collision Check
For a collision, $x_A(t) = x_B(t)$ and $y_A(t) = y_B(t)$ must hold for the same $t$.
1. $2+t = 2t-1 \implies t = 3$
2. Check $y$ at $t=3$:
   $y_A(3) = 8 - 3(3) = -1$
   $y_B(3) = 2(3) + 2 = 8$
Since $-1 \neq 8$, they do **not** collide.

## Minimum Distance
Distance squared $D^2(t) = (x_A-x_B)^2 + (y_A-y_B)^2$:
$D^2(t) = (3-t)^2 + (6-5t)^2 = 26t^2 - 66t + 45$
Derivative: $\frac{d(D^2)}{dt} = 52t - 66 = 0 \implies t \approx 1.27 \text{ s}$.
Minimum distance: $D = \sqrt{26(1.27)^2 - 66(1.27) + 45} \approx 1.76 \text{ units}$.
