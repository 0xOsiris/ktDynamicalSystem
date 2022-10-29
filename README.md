
## Mathematical Formalization
This repository builds the core foundational logic to build a dynamical system from mapping of curvature and torsion of image of parametric planar curve when stereographically projected to the unit sphere. </br>

Let $\alpha(t)$ be a an arbitrary parametric curve residing the plane $z=-1$. This will be the seed to our dynamical system. Suppose we have some mapping $\beta: \mathbb{R}^2->\mathbb{R}^3$ such that $\beta(\alpha(t))$ represents the [stereographic projection](https://en.wikipedia.org/wiki/Stereographic_projection) of $\alpha(t)$ onto the unit sphere. Notice first that this projection of now has [curvature](https://mathworld.wolfram.com/Curvature.html) $\kappa(t)$ & some [torsion](https://mathworld.wolfram.com/Torsion.html) $\tau(t)$. Notice something very interesting the curvature $\kappa(t)$ and torsion $\tau(t)$ actually trace a smooth planar curve in the same parametric form as our original seed $\alpha(t)$, Let $\phi(t)=[\kappa(t),\tau(t), -1]$ be such curve. This represent the output of the first iterate, and the input to the second iterate of our dynamical system. The dynamical system will continue this methodology by iteratively projecting the output of each iterate and reprojecting downward the curvature and torsion in the form Let $[\kappa(t),\tau(t), -1]$.

## Analysis of Families of curves. 

Let $f: \mathbb{R}^2->\mathbb{R}^2$ is defined as $f^1(\phi(t)) = \phi^1(t)=[\kappa^1(t),\tau^1(t), -1]$ where $\kappa(t)$ and $\tau(t)$ represent the curvature and torsion of the image of $\phi^0(t)$ on the unit sphere. Then $f^n(\phi(t)) = \phi^n(t)=[\kappa^n(t),\tau^n(t)]$ would be the $n_{th}$ iterate of $f$ which would be the result of stereographically projecting $[\kappa(t),\tau(t),-1]$ and recalculating the projected curvature and torsion over $n$ iterates.

## The behavior I am hoping to Analyze

### 1
Try to find fixed points in the system --> if $\phi(t) =[x(t),y(t), -1]$ then if $f(\phi(t))=\phi^1(t)$ we have $\phi^1(t)=[\kappa(f(\phi(t)),\kappa(f(\phi(t))]=\phi(t)$. The above result would be the case when $\phi(t)$ represents a planar parametric circle, but is there other cases where this could be true? To be honest, I am not sure.. but I want to know 🧙‍♂️🧙‍♂️.
### 2
Does convergence happen for some curves over an orbit of high order. Further what is the curve that the orbit of 
$f^n(\phi(t))$ is converging to. Is it always the same cure? Is it a circle? And what topological inferences could we learn from such a result. 

### 3
Does chaos ever arise in such a system? My intuition tells me no, but to be completely honest this is just a hunch. 

### 4
Categorizing behavior of families of curves in the dynamical system based on the results.





