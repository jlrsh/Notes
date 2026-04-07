Linear Differential Equation: [[Differential Equation|d.e.]] following form $\frac{dy}{dx} + p(x)y = Q(x)$

## Solving Linear DE's
- multiply both sides by integrating factor $I = e^{\int{P(x)dx}}$
- then, use inverse product rule
- this works because  $\frac{d}{dx}Iy = Iy' + I p(x)y$ by using properties of the derivative of $e$ 
$$
\begin{gather}
y' - 2y = 8e^{2x}; \space I = e^{\int{-2dx}} = e^{-2x}  \\
Iy' + Ip(x)y = e^{-2x}y'-2ye^{-2x} = \frac{d}{dx}(e^{-2x}y) \\
IQ(x) = 8e^{2x-2x}=8 \\
\frac{d}{dx}(e^{-2x}y) = 8 \\
e^{-2x}y =8x+C \\
y=(8x+C)e^{2x}
\end{gather}
$$
$$
\begin{aligned}
\text{Standard form:}\quad &y' + p(x)\,y = q(x) \\[6pt]
\text{IF:}\quad &\mu(x) = e^{\int p(x)\,dx} \\[6pt]
\text{Multiply:}\quad &\mu(x)y' + \mu(x)p(x)y = \mu(x)q(x) \\[6pt]
\text{Rewrite:}\quad &\frac{d}{dx}[\mu(x)y] = \mu(x)\,q(x) \\[6pt]
\text{Integrate:}\quad &\mu(x)y = \int \mu(x)\,q(x)\,dx + C \\[6pt]
\text{Solve for }y:\quad &y = \frac{1}{\mu(x)}\Bigl(\int \mu(x)\,q(x)\,dx + C\Bigr)
\end{aligned}
$$
