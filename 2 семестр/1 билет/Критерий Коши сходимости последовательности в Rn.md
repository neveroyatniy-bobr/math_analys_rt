Последовательность $x_k$ точек $\mathbb{R}^n$   сходится $\iff$ $\forall{\epsilon > 0} \to \exists{k_0}: \forall{k, m > k_0} \to \rho(x_k, x_m) < \epsilon$.

$\implies$ Пусть $\lim\limits_{k \to \infty} x_k = x_0$. Тогда
- $\forall{\epsilon > 0} \to \exists{k_0}: ((\forall{k \ge k_0} \to \rho(x_k, x_0) < \frac{\epsilon}{2}) \cap (\forall{m \ge k_0} \to \rho(x_m, x_0) < \frac{\epsilon}{2}))$.
Тогда для любых $k \ge k_0$ и $m \ge k_0$ выполняется неравенство 
- $\rho(x_k, x_m) \le \rho(x_k, x_0) + \rho(x_0, x_m) < \frac{\epsilon}{2} + \frac{\epsilon}{2} = \epsilon$.

$\impliedby$ Пусть $x_k = (\alpha_1^{(k)}, ... \alpha_n^{(k)})$. Тогда $\forall{k, m \ge k_0}$ выполняется неравенство
- $\rho(x_k, x_m) = \sqrt{(\alpha_1^{(k)} - \alpha_1^{(m)})^2 + ... + (\alpha_n^{(k)} - \alpha_n^{(m)})^2} < \epsilon$.
Поэтому при фиксированном $i = 1, 2, ..., n$ и подавно 
- $|\alpha_i^{(k)} - \alpha_i^{(m)}| \le \rho(x_k, x_m) < \epsilon$
Значит при фиксированном $i$ последовательность  $\alpha_i^{(k)}$ фундаментальна и по [[Критерий Коши]] она сходится к некоторому числу $\alpha_i^{(0)}$ По [[Лемма о покоординатных пределах]] последовательность $x_k$ сходится к $(\alpha_1^{(0)}, ... \alpha_n^{(0)})$.
