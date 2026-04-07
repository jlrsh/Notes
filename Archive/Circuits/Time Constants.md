---
aliases: []
---
Time Constant: amount of time in a circuit for specific voltage characteristics

### RC Circuits
$$\tau = RC; v_C(t) = v_c(\infty) + (v_c(t_0) - v_c(\infty))e^\frac{-(t-t_0)}{RC}$$
When $t = \tau; v_C(t) = v_C(\infty)*0.632$ when charging, or $v_c(t_0) * 0.368$ when discharging
When $t = 3\tau; v_C(t) = v_C(\infty)*0.95$, or $v_c(t_0) * 0.05$ when discharging
When $t = 5\tau; v_C(t) = v_C(\infty)*0.993$ or $v_c(t_0) * 0.007$ when discharging

### RL Circuits
$$\tau = \frac{L}{R}; i_L(t) = i_L(\infty) + (i_L(t_0) - i_L(\infty))e^\frac{-R(t-t_0)}{L}$$
When $t = \tau; i_L(t) = i_L(\infty)*0.632$ when charging, or $i_L(t_0) * 0.368$ when discharging
When $t = 3\tau; i_L(t) = i_L(\infty)*0.95$, or $i_L(t_0) * 0.05$ when discharging
When $t = 5\tau; i_L(t) = i_L(\infty)*0.993$ or $i_L(t_0) * 0.007$ when discharging

![[Pasted image 20250430215033.png]]