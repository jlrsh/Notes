Bernoulli Differential Equation: [[Differential Equation|d.e.]] following form $y' + p(x)y = Q(x)y^n$ if $n \neq 0,1$

## Solving Bernoulli DE's
- substitude $v = y^{1-n}$ and solve for $v'$
- use that to eliminate $y'$ and $y$ and solve algebraically
$$
\begin{gather} 
x^2y'+xy = y^2; \space v = y^{-1} \\
v' = -y^{-2}y' \therefore y' = -v'y^2\therefore y=1/v \therefore v = 1/y \\
y' + \frac{y}{x} = \frac{y^2}{x}\\
-v'y^2 + \frac{1}{x}\frac{1}{v}=\frac{1}{x^2}\frac{1}{v^2} \\
v' - \frac{v}{x}=\frac{-1}{x^2}
\end{gather}
$$
- solve as a [[Linear Differential Equation|Linear Differential Equation]] 

$$
\begin{aligned}
\text{Standard form:}\quad &y' + P(x)\,y = Q(x)\,y^n \\[6pt]
\text{Substitute:}\quad &u = y^{1-n},\quad y = u^{\tfrac{1}{1-n}} \\[6pt]
&\frac{du}{dx} + (1-n)\,P(x)\,u = (1-n)\,Q(x) \\[6pt]
\text{Solve for }u(x)\text{ (linear)} \\[6pt]
\text{Back‐substitute:}\quad &y = u^{\tfrac{1}{1-n}}
\end{aligned}
$$
