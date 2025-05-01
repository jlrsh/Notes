AC circuits: circuits that use sinuosidal current instead of static

In linear systems, **only magnitude and phase matters** as output will have same frequency as input

Sources with the same frequency can be combined, but phase must be considered
$$A \cos (\omega t + \alpha) + B \cos (\omega t + \beta) =X \cos(\omega t + \phi)$$
$$X = \sqrt{(A\cos\alpha + B\cos\beta)^2 + (A\sin\alpha + B\sin\beta)^2}$$
$$\phi = \arctan(\frac{A\sin\alpha + B\sin\beta}{A\cos\alpha + B\cos\beta})$$

- All concepts of DC circuits apply to AC circuits including [[Mesh Analysis|Mesh Analysis]], [[Nodal Analysis|Nodal Analysis]], [[Thevenin & Norton|Thevenin & Norton]], [[Linearity|Superposition]], etc
- For circuits with sources at the same frequency, we can combine [[Phasors|Phasors]]
	- Some questions might use $\sin$ instead of $\cos$ but $\sin 90 \deg = \cos 0 \deg$
- For circuits with sources at differing frequencies, we can use [[Linearity|superposition]]
	- Short other voltage sources and gap other current sources
	- Find unknowns per source and sum them
- [[Source Transformation|Source Transformation]] is identical to DC circuits
- [[Power|Power]] is calculated identically to dc but with sinuosids
	- $p(t) = v(t) i(t) = V_M I_M \cos(\omega t + \theta_v) \cos(\omega t + \theta_i) = \frac{V_m I_m}{2}(\cos(2\omega t + \theta_v \theta_i) + cos(\theta_v - \theta_i))$
	- $p_{avg} = \frac{V_m I_m}{2} \cos(\theta_v - \theta_i)$ or the real component of 0.5 * voltage * current
		![[Pasted image 20250501020940.png]]