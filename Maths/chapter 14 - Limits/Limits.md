
Used to find approximate value of a function at a point where it is not defined

ex: $f(x) = \frac{1}{x}$

clearly $f(0)$ does not exist

so a might nbd would be $x = 0.001$

lft nbd would be $x = -0.001$

$f(x) = \frac{x^2 - 4}{x - 2}$

$\lim_{x \to 2} f(x)$ / LHL = $\lim_{x \to 2^-} f(x) \Rightarrow \lim_{h \to 0} f(2-h)$

RHL = $\lim_{x \to 2^+} f(x) \Rightarrow \lim_{h \to 0} f(2+h)$

If LHL = RHL = finite value, limit exists

---
 Methods of Finding Limits

**Methods of finding limits**

1. substitution
2. factorization
3. By rationalization
4. By formulae

**a) Evaluate** $\lim_{x \to 0} \frac{|x|}{x}$

LHL $\lim_{x \to 0^-} \frac{-x}{x} = -1$

RHL = 1

RHL ≠ LHL limit does not exist

**b) Eval** $\lim_{x \to 4} \frac{|x-4|}{x-4}$

$f(x) = \frac{|x-4|}{x-4}$

$\lim_{x \to 4^-} f(x) = \lim_{h \to 0} f(4-h) = \frac{|4-h-4|}{4-h-4} = \frac{|-h|=-1}{-h}$

$\lim_{x \to 4^+} f(x) = \lim_{h \to 0} f(4+h) = \frac{|4+h-4|}{4+h-4} = \frac{|h|=1}{h}$

LHL ≠ RHL limit does not exist

# Limit Problems

**a) Evaluate** $\lim_{x \to 0} f(x) = \begin{cases} 1 & \text{if } x \geq 0 \ 1+x & \text{if } x > 0 \end{cases}$

LHL: $\lim_{x \to 0^-} f(x) = \lim_{x \to 0^-} (1) = 1$

RHL: $\lim_{x \to 0^+} f(x) = \lim_{x \to 0} (1+x) = 1$

limit exists

---

**e)** $f(x) = \begin{cases} x \leq 0 \ \lfloor x \rfloor, & 0 \leq x \leq 1, \ {3}x & x > 1 \end{cases}$

**find** $\lim_{x \to 0} f(x)$ **at** $x = 0$ **&** $1$

$\lim_{x \to 0^-} f(x) = \lim_{x \to 0^-} (x + 1) = 1$

$\lim_{x \to 1^-} f(x) = \lim_{x \to 1^-} (2x + 1) = 1$

$\lim_{x \to 0^+} f(x) = \lim_{x \to 0^+} (2n+1) = 1$

$\lim_{x \to 1} \text{ at } x = 1$

LHL = RHL at $x = 0$

$\lim_{x \to 1^-} f(x) = \lim_{x \to 1^-} (2x+1) = 3$

$\lim_{x \to 1^+} f(x) = \lim_{x \to 1^+} (3x) = 3$

LHL = RHL limit exists