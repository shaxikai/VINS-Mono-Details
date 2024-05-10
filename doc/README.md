# VINS 学习

[IMU预积分](./IMU预积分/)

$$
\begin{aligned}\mathbf{p}_{b_{k+1}}^w=\mathbf{p}_{b_k}^w+\mathbf{v}_{b_k}^w\Delta t_k+\iint_{t\in[t_k,t_{k+1}]}(\mathbf{R}_t^w(\hat{\mathbf{a}}_t-\mathbf{b}_{a_t}-\mathbf{n}_a)\end{aligned}
 $$ 
