$(1+x)^n = {}^nC_0 x^0 + {}^nC_1 x + {}^nC_2 x^2 + \dots + {}^nC_n x^n$

$(1-x)^n = {}^nC_0(-x)^0 + {}^nC_1(1x) + {}^nC_2(1x)^2 + \dots + {}^nC_n(1x)^n(-1)^n$

Put $x=1$:

$2^n = {}^nC_0 + {}^nC_1 + {}^nC_2 + \dots + {}^nC_n \quad (i)$

$0 = {}^nC_0 - {}^nC_1 + {}^nC_2 - \dots + {}^nC_n x^n(-1)^n \quad (ii)$

(i) $\Rightarrow$ total no. of ways of selecting $n$ objects

For at least one object (${}^nC_0$ is not possible), so $2^n - 1$

**Adding (i) and (ii):**

$2^n = 2[{}^nC_0 + {}^nC_2 + {}^nC_4 + \dots]$

$2^{n-1} = {}^nC_0 + {}^nC_2 + {}^nC_4 + \dots$
(sum of even coefficients)

**Subtracting (i) and (ii):**

$2^n = 2[,{}^nC_1 + {}^nC_3 + {}^nC_5 + \dots]$

$2^{n-1} = {}^nC_1 + {}^nC_3 + {}^nC_5 + \dots$
(sum of odd coefficients)

---

**Prove:**

${}^nC_1 + 2{}^nC_2 x^1 + 3{}^nC_3 x^2 + 4{}^nC_4 x^3 + \dots + n{}^nC_n x^{n-1} = n(1+x)^{n-1}$

If we **differentiate** both sides to reduce power in:

 $(1+x)^n = {}^nC_0 + {}^nC_1 x + {}^nC_2 x^2 + \dots + {}^nC_n x^n$

we get first expression.

---

**Theorem:**

Prove $a,C_0 + (a+d),C_1 + (a+2d),C_2 + \dots + (a+nd),C_n = (2a+nd),2^{n-1}$

Let $S = a,C_0 + (a+d),C_1 + \dots + (a+nd),C_n$

Now we reverse the order, we get:

$S = (a+nd),C_n + (a+(n-1)d),C_{n-1} + \dots + (a+d),C_1 + a,C_0$

$S = (a+nd),C_0 + (a+(n-1)d),C_1 + \dots + (a+d),C_{n-1} + a,C_n$

( $C_0 = C_n$, $C_1 = C_{n-1}$)

Adding both:

$2S = (2a+nd)(C_0 + C_1 + C_2 + \dots + C_n)$

$2S = (2a+nd)2^n$

$S = (2a+nd)2^{n-1}$

[[Binomial Theorem for Rational n]]