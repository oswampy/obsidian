A progression of non-zero terms in which every term bears to the preceding term a constant ratio. Ex- 2,4,8,16

- a is first term
- r is common ratio
- n is nth term (can only be +ve integers)
- $T_{n} = ar^{n-1}$
- $S_{n} = \frac{a(r^{n}-1)}{r-1}$ (n $\ne1$otherwise it would be an AP with $S_{n}=na$)
- $S_{\infty} = \frac{a}{1-r}$($-1<r<1$)
- if $x_{1},x_{2},x_{3}$ is a g.p of +ve terms then $\log x_{1},\log x_{2},\log x_{3}$ is an A.P and vice versa
	proof: $x_{1},x_{2}=x_{1}r,x_{3}=x_{1}r^2$
	$\log x_{2}=\log x_{1}+\log r\;$ and$\;\log x_{3}=\log x_{1}+2\log r$
	A.P with d = $\log r$
- Observations on G.P:

| a   | r     | result     |
| --- | ----- | ---------- |
| a>0 | r>1   | Increasing |
| a>0 | 0<r<1 | Decreasing |
| a<0 | r>1   | Decreasing |
| a<0 | 0<r<1 | Increasing |

---
## Solved Examples

Q) which term of 2,1,1/2,1/4 is 1/128
A) a=2, r=1/2
	$\frac{1}{128} = 2*\left( \frac{1}{2} \right)^{n-1}$
	$\frac{1}{2^8}=\frac{1}{2}^{n-1}$
	$2^8=2^{n-1}$
	$n = 9th\;term$

Q)Find 4 nos in G.P such that third term exceeds the first by 9 and 2nd exceeds 4th by 18
A)$T_{3}=T_{1}+9$ and $T_{2}=T_{4}+18$
	$g.p-a,ar,ar^2,ar^3$
	$ar^2=a+9$ and $ar=ar^3+18$
	$a(r-1)(r+1)=9$ and $ar(r-1)(r+1)=18$
	dividing 2nd by the 1st
	$r=-2$
	putting r in an equation
	$\implies 3,-6,12,-24$

Q) if the pth, qth and rth terms of a GP are x,y,z respectively then find prove:
$x^{q-r}y^{r-p}z^{p-q}=1$
A) for products to be one, everything has to be one, so powers add to 0
	$x=pth term\implies ab^{p-1}$
	$y=ab^{q-1}$
	$z=ab^{r-1}$
	in eq all variables have a power to we apply that to each term seperately
	$x^{q-r}=a^{q-r}b^{(p-1)(q-r)}$
	$y^{r-p}=a^{r-p}b^{(q-1)(r-p)}$
	$z^{p-q}=a^{p-q}b^{(r-1)(p-q)}$
	multiplying all terms
	$x^{q-r}y^{r-p}z^{p-q}$
	$\implies a^{0}b^0=1$

Q)prove for a g.p $T_{m+n}*T_{m-n}=T_{m}^2$
A)$T_{m+n}=ar^{m+n-1}$
	$T_{m-n}=ar^{m-n-1}$
	$T_{m+n}*T_{m-n}= a^2r^{2(m-1)}$
	$\implies (ar^{m-1})^{2}= T_{m}^2$

Q)sum of n terms whose nth term is $2^{n}+ 3n$
A) we have a G.P and A.P
	G.P-$2^n$ in this sequence the first term a=2 and each term has the same r=2
	A.P-$3n$ in this sequence the first term a=3 and each term differs by d=3
	making both sums individually
	$\frac{2(2^{n}-1)}{2-1}+\frac{6}{2}(4+3(n-1))$
	$\implies \frac{2(2^{n}-1)}{2-1}+3(1+3n)$

Q)find sum of 5+55+555... to n terms
A) in case of same digit, take digit common, then make 9 by dividing and multiplying
	$5[1+11+111\dots n]$
	$\frac{5}{9}[9+99+999\dots n]$
	$\frac{5}{9}[10+(10^2-1)+(10^3-1)..n]$
	split into GP(a=10,r=10) and AP(a=1,d=0)
	$\frac{5}{9}\left[ \frac{10(10^{n}-1)}{10-1}-n \right]$ (n because whats left is a sum of 1s n times)
	$\implies\frac{5}{81}[10^{n+1}-10-9n]$

Q) if each term of an infinite G.P is twice the sum of following terms, find common ratio
A) $T_{2}=2[T_{3}+T_{4}\dots \infty]$
	$ar^{n-1}=2[ar^n+ar^{n+1}...\infty]$
	inf G.P with a = $ar^n$ and ratio = $r$
	$ar^{n-1}= \frac{2ar^n}{1-r}$
	$\frac{1}{2}=\frac{2}{1-r}$  ($r^n-1=\frac{r^n}{r}$)
	$\implies r = \frac{1}{3}$
	