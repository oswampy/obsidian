Series that are not AP,GP,HP or AGP are termed as special series

**Summation Equations:**

$$\begin{aligned}
\sum_{r=1}^{n} r   &= \frac{n(n+1)}{2} \\
\sum_{r=1}^{n} r^2 &= \frac{n(n+1)(2n+1)}{6} \\
\sum_{r=1}^{n} r^3 &= \left( \frac{n(n+1)}{2} \right)^2
\end{aligned}$$


---

## Solved Examples

Q) Sum of n terms of series 3+7+14+24...
A) we can see that the common difference of the terms are in AP 
	We use formula when d is in AP:
		$T_{n}=an^2+bn+c$
		since there are three variables we need 3 equations
	$3=a+b+c$
	$7=4a+2b+c$
	$14=9a+3b+c$
	On solving:
	$a=\frac{3}{2},b=\frac{-1}{2},c=2$
	$T_{n}=\frac{1}{2}(3n^2-n+4)$
	using summation formulas:
	$\sum T_{n}=\frac{1}{2}\left( 3\sum n^2-\sum n+\sum4 \right)$
	$\boxed{S_{n}=\frac{n}{2}(n^2+n+4)}$
	