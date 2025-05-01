Inductors: an element that resists changes in current
$$v_L(t) = L \frac{di_L(t)}{dt}; i_L(t) = i_L(t_0) + \frac{1}{L}\int_{t_0}^{t}v_L(x)dx; W_L = \frac{1}{2}Li_L^2(t)$$

- Steady: inductors block all current from passing through but let all voltage through
- Charging: $i_L(t) = V_0 (1-e^\frac{-tR}{L})$ and 
- Discharging: $V_C(t) = I_0 e^\frac{-tR}{L}$
- $I(t) = V_0e^\frac{-tR}{L}$ when $t \neq 0$
### Inductors in Parallel
$$L_{eq} = \frac{1}{\sum \frac{1}{L_n}} = \frac{L_1*L_2}{L_1 + L_2}$$
*$L_{eq}$ = equivalent inductance, $L_n$ = inductance per inductor, $L_1 / L_2$ = inductance of inductor 1 & 2*

### Inductors in Series
$$L_{eq} = \sum L_n$$
*$L_{eq}$ = equivalent inductance, $L_n$ = inductance per inductor*
