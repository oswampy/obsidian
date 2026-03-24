

$$\text{Slope} = \frac{\Delta y}{\Delta x} = \frac{y_2 - y_1}{x_2 - x_1}$$

Let $y = f(x)$ $y_1 = f(x_1)$ $y_2 = f(x_2)$

$$\frac{f(x_2) - f(x_1)}{x_2 - x_1}$$ where $x_1$ is given point and $x_2$ is $x^+ \text{ or } x^-$

LHD of function as $x \to a$

$$\text{LHD} = \lim_{h \to 0} \frac{F(a-h) - F(a)}{(a-h) - a}$$

$$\text{RHD} = \lim_{h \to 0} \frac{F(a+h) - F(a)}{(a+h) - a}$$

If LHD = RHD $\Rightarrow f(x)$ is differentiable at $x = a$ (finite value)

---

$$f(x) = |x|$$

This function has multiple tangents at $x = 0$ (sharp edge or corner point)

$\therefore f(x) = |x|$ is non differentiable at $x = 0$

---

## First principle of Derivatives

a) **Differentiate** $\sin x$

$$(\sin x)' = \lim_{h \to 0} \frac{F(x+h) - F(x)}{x+h-x}$$

$$\lim_{h \to 0} \frac{\sin(x+h) - \sin x}{h}$$

$$\lim_{h \to 0} \frac{2\cos\left(\frac{2x+h}{2}\right) \sin\left(\frac{h}{2}\right)}{h}$$

$$\lim_{h \to 0} \cos x$$

---

b) **Differentiate** $\cos x$

$$\lim_{h \to 0} \frac{\cos(x+h) - \cos(x)}{x+h-x}$$

$$\lim_{h \to 0} \frac{-2\sin\left(\frac{2x+h}{2}\right) \sin\left(\frac{h}{2}\right)}{h \times 2}$$

$$\lim_{h \to 0} \frac{\sin(x+h) \cos(x) - \sin(x) \cos(x+h)}{\cos(x) \cos(x+h)} \times \frac{1}{h}$$

$$\lim_{h \to 0} \frac{\sin(h)}{h \cos^2 x}$$

$$= \sec^2 x$$

---

c) **Differentiate** $\tan x$

$$\lim_{h \to 0} \frac{\frac{\sin(x+h)}{\cos(x+h)} - \frac{\sin(x)}{\cos(x)}}{h}$$

$$\lim_{h \to 0} \frac{\cos(x+h)\sin(x) - \cos(x)\sin(x+h)}{\sin^2 x} \times \frac{1}{h}$$

$$\lim_{h \to 0} \frac{\sin(-h)}{h \sin^2 x} = -\csc^2 x$$

---

d) **Differentiate** $\cot x$

$$\lim_{h \to 0} \frac{\frac{\cos(x+h)}{\sin(x+h)} - \frac{\cos(x)}{\sin(x)}}{h}$$

$$\lim_{h \to 0} \frac{\cos(x+h)\sin(x) - \cos(x)\sin(x+h)}{\sin^2 x} \times \frac{1}{h}$$

$$\lim_{h \to 0} \frac{\sin(-h)}{h \sin^2 x} = -\csc^2 x$$

---

e) **Differentiate** $\sin\sqrt{x}$

$$\frac{\sin\sqrt{x+h} - \sin\sqrt{x}}{(\sqrt{x+h}) - \sqrt{x}}$$

$$x + h = (\sqrt{x+h})^2$$

$$x = (\sqrt{x})^2$$

$$2\sin\sqrt{x+h} - \sqrt{x} \cos\left(\sqrt{x+h} + \sqrt{x}\right)$$

$$\frac{(\sqrt{x+h} + \sqrt{x}) + (\sqrt{x+h} - \sqrt{x}) \times 2}{2}$$

$$\Rightarrow \frac{\cos\sqrt{x}}{2\sqrt{x}}$$

---

f) **Differentiate** $\sqrt{\sin 2x}$

$$\lim_{h \to 0} \frac{\sqrt{\sin 2x + 2h} - \sqrt{\sin 2x}}{2h}$$

$$\lim_{h \to 0} \frac{\sin(2x+2h) - \sin 2x}{2h(\sqrt{\sin 2x+h} + \sqrt{\sin 2x})}$$

$$\lim_{h \to 0} \frac{2\sin(h) \cos(2x+h)}{2h(\sqrt{\sin 2x+h} + \sqrt{\sin 2x})}$$

$$\lim_{h \to 0} \frac{2\cos 2x}{2\sqrt{\sin 2x}}$$

$$= \frac{\cos 2x}{\sqrt{\sin 2x}}$$

---

