# 运算

## 常见运算符

```latex
+, -, \pm, \mp, \dotplus, \cdot, \times, \div, /, \backslash
```

$$
+, -, \pm, \mp, \dotplus, \cdot, \times, \div, / ,\backslash
$$

## 关系符号

```latex
=, \ne, \equiv, \overset{\mathrm{def}}{=}, :=, \sim, \cong, \approx
```

$$
=, \ne, \equiv, \overset{\mathrm{def}}{=}, :=, \sim, \cong, \approx
$$

```latex
\leqslant, \geqslant
```

$$
\leqslant, \geqslant
$$

## 根号

```latex
\surd, \sqrt{2}, \sqrt[a]{b}
```

$$
\surd, \sqrt{2}, \sqrt[a]{b}
$$

## 分数

```latex
\frac{a}{b}, \frac{\frac{a}{b}}{c}, \cfrac{\cfrac{a}{b}}{c}
```

$$
\frac{a}{b},\frac{\frac{a}{b}}{c}, \cfrac{\cfrac{a}{b}}{c}
$$

## 极限

```latex
\min, \max, \lim, 
```

$$
\min, \max, \lim, \lim_{x\to0}, 
$$



## 导数与微分

```latex
\prime, \backprime, f^\prime, f', f'', f^{(3)}, \dot y, \ddot y
```

$$
\prime, \backprime, f^\prime, f', f'', f^{(3)}, \dot y, \ddot y
$$

```latex
dt, \mathrm{d}t, \partial t, \nabla, \delta, \Delta, \psi
```

$$
dt, \mathrm{d}t, \partial t, \nabla, \delta, \Delta,\psi
$$

## 集合

```latex
\cap， \bigcap， \cup, \bigcup, \in, \notin, \not\in \ni, \not\ni
```

$$
\cap, \bigcap, \cup, \bigcup, \in, \notin, \not\in, \ni, \not\ni
$$



# 特殊符号

## 类字母符号与常数

```latex
\infty, 
```

$$
\infty,
$$

## 希腊符号

```latex
\alpha, \beta, \gamma, \delta, \epsilon, \zeta, \eta, \theta,
```

$$
\alpha, \beta, \gamma, \delta, \epsilon, \zeta, \eta, \theta,
$$

```latex
\lambda, \mu, \nu, \omicron, \xi, \pi, \rho, \sigma, \tau, 
```

$$
\lambda, \mu, \nu, \omicron, \xi, \pi, \rho, \sigma, \tau,
$$

```latex
\upsilon, \phi, \chi, \omega,
```

$$
\upsilon, \phi, \chi, \omega
$$

### 部分字母的变量专用形式

```latex
\varepsilon， \digamma， \varkappa， \varpi，
```

$$
\varepsilon， \digamma， \varkappa， \varpi，
$$

```latex
\varrho, \varsigma, \vartheta, \varphi,
```

$$
\varrho, \varsigma, \vartheta, \varphi,
$$

## 逻辑符号

```latex
\forall, \exists, \nexists,\therefore, \because, \And, \or,\and, \lnot
```

$$
\forall, \exists, \nexists, ~\therefore~\because~\And, \or, \and, \lnot
$$



## 括号

```latex
\langle, \rangle, 
```

$$
\langle, \rangle, 
$$

## 空格

```latex
\quad, \qquad, ~
```



# 排版

$$
\begin{align}
We~want~to~show~that:& \qquad	
\lim_{x\to{x_0}}f(x)-f(x_0)=0	\\

From~f~is~differentiable:& \qquad
\lim_{x\to{x_0}}\frac{f(\Delta{x}+x_0)-f(x_0)}{\Delta{x}}=f'(x)	\\
\\
So:&
\\


\lim_{x\to{x_0}}f(x)-f(x_0)
&=\lim_{x\to{x_0}}\frac{f(x)-f(x_0)}{x-x_0}(x-x_0)	\\
&=f'(x_0)\cdot0	\\
&=0	
\end{align}
$$



# 数组与表格

```latex
\begin{array}{cc|l|c|r|}
n & n & left & center & right	\\
\hline
1 & 1 & ab   & ab	  & ab	\\
1 & 1 & abcdefgh   & abcdefgh	  & abcdefgh	\\
\end{array}
```

$$
\begin{array}{cc|l|c|r|}
n & n & left & center & right	\\
\hline
1 & 1 & ab   & ab	  & ab	\\
1 & 1 & abcdefgh   & abcdefgh	  & abcdefgh	\\
\end{array}
$$

