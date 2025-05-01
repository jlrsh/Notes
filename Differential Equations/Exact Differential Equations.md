Exact Differential Equations: [[Differential Equation|d.e.]] following form $Mdx + Ndy = 0$ where $\frac{\partial M}{\partial y} = \frac{\partial N}{\partial x}$

## Solving Exact DE's
- to begin, prove that DE is exact
$$\begin{gather} 
(3x^2+2y^2) dx + (4xy+6y^2)dy = 0 \\
M = 3x^2 + 2y^2; \space N = 4xy+6x^2 \\
M_y = N_x = 4y
\end{gather}$$
- take both mixed partial derivative of function
$$\begin{gather}
\frac{\partial f}{\partial x} = M = 3x^2 + 2y^2; \space \frac{\partial f}{\partial y} = N = 4xy +6x^2 \\
f = \int Mdx = x^3 + 2y^2x + g(y) + C = \int Ndy = 2y^2x + 2y^3 + g(x) + C \\
g(y) = 2y^3; \space g(x) = x^3 \\
f = x^3 + 2y^2x + 2y^3 + C
\end{gather}$$
$$
\begin{aligned}
\text{Given:}\quad &M(x,y)\,dx + N(x,y)\,dy = 0 \\[6pt]
\text{Check exactness:}\quad &M_y = N_x \\[6pt]
\text{Integrate:}\quad &\Psi(x,y) = \int M(x,y)\,dx + h(y) \\[6pt]
&\text{then determine }h(y)\text{ from }\Psi_y = N \\[6pt]
\text{General solution:}\quad &\Psi(x,y) = C
\end{aligned}
$$