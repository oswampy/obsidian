any case of both AP and GP
$1+3x+5x^2+7x^3\dots$
1,3,5,7 are in AP and $x,x^2,x^3$ are in GP
generalised as:
$a+(a+d)r+(a+2d)r^2+(a+3d)r^3\dots[a+(n-1)d]r^{n-1}$

- Sum of infinite terms of A.G.P:
	$S_{\infty}=\frac{a}{1-r}+\frac{dr}{(1-r)^2}$
	
**NOTE: sum till n terms does NOT mean sum of infinite terms**

---
## Solved Examples

Q) sum of $S=1+\frac{4}{5}+\frac{7}{5^2}+\frac{10}{5^{3}}\dots n\;terms$
A)common process for these qs: 
	i) multiply by common ratio r
	ii) put similar terms below each other
	iii)subtract terms, dont forget initial term
	$S=1+\frac{4}{5}+\frac{7}{5^2}+\frac{10}{5^{3}}\dots n\;terms$
	$\frac{S}{5}=0+\frac{1}{5}+\frac{4}{5^2}+\frac{7}{5^3}\dots \frac{T_{n}}{5}$
	$T_{n}$ will be nth term of ap divided by the ratio till n-1(observing pattern)
	$T_{n}=\frac{3n-2}{5^{n-1+1}}$
	subtracting:
	$S- \frac{S}{5}=1+\frac{3}{5}+\frac{3}{5^2}+\frac{3}{5^3}$
	$\frac{4S}{5}=1+3\left[ \frac{1}{5}+\frac{1}{5^2}\dots n-1\;terms \right]$(excluding the first 1 so n-1)
	$\frac{4S}{5}=1+3\left[ \frac{\frac{1}{5}\left( 1- \frac{1}{5}^{n-1} \right)}{1- \frac{1}{5}} \right]$
	$\frac{4S}{5}=1+\frac{3}{4}\left[ 1- \frac{1}{5}^{n-1} \right]$
	$S= \frac{5}{16}\left[ 1+3\left( 1- \left( \frac{1}{5} \right)^{n-1} \right) \right]$


[[A.P]]
[[G.P]]