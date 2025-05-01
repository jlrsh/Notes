Homogeneous Differential Equation: [[Differential Equation|d.e.]] that follows form $\frac{dy}{dx}=f(\frac{y}{x})$

### Solving Homogenous DE's
- can substitute into either [[Separable Differential Equation|separable d.e.]] or [[Linear Differential Equation|linear d.e.]]

$$
\begin{aligned}
\text{Given:}\quad &\frac{dy}{dx} = \frac{x - y}{x + y} \\[6pt]
\text{Substitute:}\quad &v = \tfrac{y}{x}, \quad y = vx, \quad \frac{dy}{dx} = v + x\frac{dv}{dx} \\[6pt]
\text{Gives:}\quad &v + x\frac{dv}{dx} = \frac{1 - v}{1 + v} \\[6pt]
\text{Rearrange:}\quad &x\frac{dv}{dx} = \frac{1 - v}{1 + v} - v
= \frac{1 - 2v - v^2}{1 + v} \\[6pt]
\text{Separate:}\quad &\frac{1 + v}{1 - 2v - v^2}\,dv = \frac{dx}{x} \\[6pt]
\text{Integrate:}\quad &\int \frac{1 + v}{1 - 2v - v^2}\,dv = \ln\lvert x\rvert + C \\[6pt]
\text{Back-substitute:}\quad &v = \tfrac{y}{x},\;\text{then solve for }y.
\end{aligned}
$$