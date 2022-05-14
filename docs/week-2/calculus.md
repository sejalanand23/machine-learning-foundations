# Week 2

## Functions, Continuity and Differentiability Pointers

- For a real-valued function, co-domain is $\mathbb{R}$.
- A function is said to be continuous in $\mathbb{R}$ if it is continuous at all points in $\mathbb{R}$.
- If a function is differentiable at a point, then it is also continuous at that point.
- If a function is not differentiable at a point, then it may or may not be continuous at that point.
- If a function is not continuous at a point, then it is not differentiable at that point.
- A function $f(x)$ is continuous at a point $x_i$ if for any sequence of $x_i$ converging to $x_0$, $f(x_i)$ converges to $f(x_0)$.
- Higher order approximations are more accurate than linear approximation.
- The plot of linear approximation of a function $f$ at a point $v$ is tangent to $f$ at the point $(v,(f(v))$.

## Vectors Pointers

- If the vectors $u$ and $v$ belong to a vector space $V$, then their linear combination belongs to $V$
- Two vectors $x$ and $y$ are perpendicular to each other if
    - $x.y = 0$
    - $x^Ty = 0$
- $[0,0,0]$ is perpendicular to any given vector.
- A hyperplane normal to a vector $w$ with offset value $b$ is given by ${x: w^Tx = b}$.
- A line through a point $u$ along vector $v$ is given by ${x:x = u + \alpha v}$.
- $x^Ty = x.y = \sum_{i=1}^d x_iy_i$

### Length of a Vector $u(x,y)$

$\lVert u \rVert = \sqrt{x^2+y^2}$

### Linear approximation of univariate functions

The linear approximation of a function $f(x)$ at point $a$ is given as:

$$
⁍
$$

### Linear approximation of multivariate functions

The linear approximation of a function $f$ of two variables $x$ and $y$ in the neighbourhood of $(a,b)$ is:

$$
L(x,y) =f(a,b) + \frac{\partial f}{\partial x}(a,b)(x-a) + \frac{\partial f}{\partial y}(a,b)(y-b) 
$$

### Gradient of a function

- Gradient of a function evaluated at a point is a vector.
- It points in the direction of the steepest ascent.
- Gradient of a function at a point is perpendicular to the contour through the point.

$$
\nabla f(x,y) = [\frac{\partial f(x,y)}{\partial x},\frac{\partial f(x,y)}{\partial y}]
$$

### Finding Directional Derivative

Finding directional derivative of a function $f(x,y)$ at a point $(a,b)$ in the direction of the vector $<u,v>$

1. Find $\nabla f(x,y)$.
2. Find $\nabla f(a,b)$
3. Convert $<u,v>$ to unit vector.
4. Directional Derivative = Dot product of $\nabla f(a,b)$ and $<u,v>$.

### Direction of steepest accent

$$
\frac{\nabla f(a,b)}{\lVert\nabla f\rVert}
$$

### Equation of a line passing through points $a$ and $b$

$$
[x,y,z] = a + \alpha (b-a)

$$

or

$$
[x,y,z] = b + \alpha (a-b)
$$