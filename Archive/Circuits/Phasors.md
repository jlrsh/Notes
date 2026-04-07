Phasors: representation of [[AC Circuits|AC]] keeping only magnitude and phase

$$X = a + jb = r\angle\theta = re^{j\theta}$$
*$a$ = real number, $b$ = imaginary part, $r$ = magnitude, $\theta$ = angle ($-\pi, \pi$]*
![[Pasted image 20250501002008.png]]

$$a = |X| \cos(\angle X)) = r \cos \theta, b = |X| \sin(\angle X) = r \sin \theta$$
$$r = \sqrt{a^2 + b^2}, \theta = \arctan(\frac{b}{a})$$


## Phasor Operations
### Addition and Subtraction
Rectangular form is simple: $$X = a + jb, Y = c + jd, X-Y = (a-c) + j(b-d), X+Y = (a+c) + j(b+d)$$

### Multiplication and Division
Polar form is simple: $$X = r_1 \angle \theta_, Y = r_2 \angle \theta_2, XY = r_1 r_2 \angle \theta_1 + \theta_2, \frac{X}{Y} = \frac{r_1}{r_2}\angle \theta_1 - \theta_2$$
### Other Operations
$$\frac{1}{X} = \frac{1}{r}\angle - \theta; \sqrt{X} = \sqrt{r} \angle \frac{\theta}{2}; X^\frac{1}{n} = r^\frac{1}{n} \angle \frac{\theta}{n}$$
$$j = 1\angle 90\deg; \frac{1}{j} = -j = 1\angle{-90\deg}$$

### Example
$$X_1 = 1 + j, X_2 = 1-j, X_3 = -1-j, X_4 = -1 + j$$
![[Pasted image 20250501002414.png]]
$$|X_1| = |X_2| = |X_3| = |X_4| = \sqrt{2}$$
$$\theta_1 = \arctan(\frac{1}{1}) = 45 \deg$$
$$\theta_2 = \arctan(\frac{-1}{1}) = -45 \deg$$
$$\theta_3 = \arctan(\frac{-1}{-1}) = 45 \deg \neq \theta_3$$
As seen from the picture, $\theta_3 = -135 \deg \neq -45 \deg$
Same with $\theta_4$ where it's actually $135 \deg$ and not $-45 \deg$
![[Pasted image 20250501002827.png]]