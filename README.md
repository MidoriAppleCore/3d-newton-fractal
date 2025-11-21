To the best of my knowledge, this framework of interpreting a parameter-indexed family of Newton fractals as a continuous 3D structure formed by stacking slices along the parameter axis has not been explored in detail in the existing literature. I’m sharing it here in the hope that someone with a stronger mathematical background might pick it up and take it further. If you do, let me know! I’ve been obsessed Newton fractals for more than a decade, and I’d love to see what you make of this idea.

When extending a Newton fractal into three dimensions, we introduce a parameter $t$ that acts as a third spatial coordinate. Consider the family of functions

$$
f(z,t) = z^3 - tz - 1,
$$

where $z \in \mathbb{C}$ and $t$ is a real (or complex) parameter.

For each fixed value of $t$, we examine the Newton iteration in the complex plane:

$$
N_t(z) = z - \frac{f(z,t)}{f'_z(z,t)}
       = z - \frac{z^3 - tz - 1}{3z^2 - t}.
$$

This produces the familiar 2D Newton fractal corresponding to the slice defined by that specific $t$.

If we interpret $t$ as a spatial coordinate — the **z-axis** — while the complex plane of $z$ provides the **x** and **y** axes, then varying $t$ continuously generates a stack of infinitesimally thin Newton fractal slices. As these slices accumulate, they form a three-dimensional structure.

Viewed this way, the full collection of points $(x,y,t)$ for which $x + iy$ lies in the Newton fractal for parameter $t$ forms a continuous surface-like object in 3D space. This can be regarded as a **worldsheet** traced out by the evolution of the Newton fractal as the parameter $t$ varies.
