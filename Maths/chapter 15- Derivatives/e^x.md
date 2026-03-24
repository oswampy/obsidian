

**a) Differentiate e^n using First principle**

$$\lim_{h \to 0} \frac{e^{(n+h)} - e^n}{h} = e^n \cdot \frac{e^h - 1}{h} = e^x$$

**b) Diff e^(√2x)**

$$\lim_{h \to 0} \frac{e^{√(2x+h)} - e^{√2x}}{h}$$

$$\lim_{h \to 0} \frac{e^{√2x}(e^{√(2x+h) - √2x} - 1)}{h}$$

$$\lim_{h \to 0} \frac{e^{√2x}(e^{√(2x+h) - √2x} - 1)}{(√(2x+h))^2 - (√2x)^2}$$

$$\lim_{h \to 0} \frac{2e^{√2x}(e^{√(2x+h) - √2x} - 1)}{(√(2x+h) + √2x)(√(2x+h) - √2x)}$$

$$\lim_{h \to 0} \frac{e^{√2x}}{√2x}$$

---

**c) lim (n→∞) [nx]/x**

We can't use normal methods so we have to prove the GIF

$$x - 1 \leq [x] \leq x$$ (Sandwich theorem)

$$\frac{x-1}{x} \leq \frac{[x]}{x} \leq 1$$

$$\lim_{x \to \infty} \frac{x-1}{x} \leq \lim_{x \to \infty} \frac{[x]}{x} \leq 1$$

both limits are 1

so $$\lim_{x \to \infty} \frac{[x]}{x} = 1$$

**d) lim (n→∞) [1/(1+n²) + 2/(1+n²) + 3/(3+n²) + ... + n/(n+n²)]**

for LHS we increase denominator

$$\frac{1 + 2 + ... + n}{n+n²} < f(n) \leq \frac{1 + 2 + 3 + ... + n}{1+n²}$$

$$\frac{n(n+1)}{2n(1+n)} = \frac{1}{2}$$

$$∴ f(x) = \frac{1}{2}$$

---


## **Product Rule**

$$(uv)' = u'v + v'u$$

$$(uvw)' = u(vw)' + (uv)'w + (uv)w'$$

**a)** $$(x^2 \sin x)' = 2x \sin x + x^2 \cos x$$

## **Quotient Rule**

$$\left(\frac{u}{v}\right)' = \frac{vu' - uv'}{v^2}$$

**b)** $$\left(\frac{\sin x}{x}\right)' = \frac{x \cos x - \sin x}{x^2}$$

**c)** $$\left(\frac{\log x}{x^{3/2}}\right)' = \frac{\frac{1}{x} \cdot x^{3/2} - \frac{3}{2} \log x \sqrt{x} \log x}{2x^3}$$

## **Chain Rule**

$$\sin √x = \frac{\cos √x}{2√x}$$