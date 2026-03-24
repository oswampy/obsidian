An expression consisting of two terms.
It is used to expand higher powers of a binomial expansion.

$$^nC_{r}=\frac{n!}{r!(n-r)!}$$
$^nC_{r}=^nC_{n-r}$
## Binomial Theorem for positive integral index
If n is a positive integer:
$(x+a)^n=^nC_{0}x^n+^nC_{1}x^{n-1}a+^nC_{2}x^{n-2}a^2\dots^nC_{r}x^{n-r}a^r\dots^nC_{n}$
Or:
$(x+a)^n=^nC_{0}a^n+^nC_{1}a^{n-1}x+^nC_{2}a^{n-2}x^2\dots^nC_{r}a^{n-r}x^r\dots^nC_{n}$
Observations:
- we start with $^nC_{0}x^n$ and go to n terms so total is n+1 terms
- the powers of x and a always sum to n
- $^nC_{0},^nC_{1},etc$ are binomial coefficients

**General Term:**
$$T_{r+1}=^nC_{r}x^{n-r}y^r$$
(r+1 because it starts at 0 , so 5th term will have r as 4)

expansion of $(a+b+c)^n=^{n+2}C_{2}$


Q) if the coefficients of $(2r+4)$th term and $(r-2)$nd term in the expansion of $(1+x)^{18}$ are equal, find r
A)using general term we get 1st term as: $T_{2r+3}$ and 2nd term as $T_{r-3}$
	$^{18}C_{2r+3}=^{18}C_{r-3}$
	 in these cases when we have $^nC_{x}=^nC_{y}$, we can either do:
		 i) x=y
		 ii)x+y=n
		 x=y would result in a negative r in this case so
	$2r+3+r-3=18$
	$r=6$


Q) A and B are coefficients of $x^n$ in expansion of $(1+x)^{2n} \;and\; (1+x)^{2n-1}$
find A:B 
A)$T_{r+1}=^{2n}C_{r}x^r$
	setting r =n so we get in form of $x^n$
	then A becomes $^{2n}C_{n}$
	same thing with the other term we get B as $^{2n-1}C_{n}$
	-$\frac{\frac{2n!}{n!(2n-n)!}}{\frac{(2n-1)!}{n!(2n-1-n)!}}$
	-$\frac{2n!}{n!}*\frac{(n-1)!}{(2n-1)!}$  ($n!=n(n-1)!$)
	$\frac{2n(2n-1)!}{n(n-1)!}*\frac{(n-1)!}{(2n-1)!}$
	$=2$

Q)Find no of irrational terms in 
$(5^{1/6}+2^{1/8})^{100}$
	A) first we find total number of terms then rational terms then subtract to get remaining irrational terms
	total terms = 101
	$^{100}C_{r}(5)^\frac{100-r}{6}(2)^{r/8}$
	for rational terms they have to be positive integer numbers
	$\therefore$ 100-r has to be a multiple of 6 and r has to be a multiple of 8
		on analysing the conditions we can see the values that satisfy both are:
		r=16,40,64,80 (if r=16 then The term will be $T_{r+1}$ so 17th term is first positive)
		total irrational terms = 101-4=**97**



[[Binomial approximation]]