**Centre of Mass (CM):**  
CM is an imaginary point where the whole mass of an object or system of particles is assumed to be concentrated.

CM of a system of particles is the imaginary point about which the sum of the moments of all masses is zero.
**Notes:**

- CM of two particles is on the line joining them.
    
- CM is closer to the heavier particle and away from the lighter particle.
    
- CM of a two-particle system divides the line joining them in the inverse ratio of their masses.
- Force of gravitation always acts on CM
-dia
	![[CM dia.excalidraw]]
Equations:

- $r_c + r_{1c} = r_1$
- $r_c + r_{2c} = r_2$
- $r_{1c} = r_1 - r_c$
- $r_{2c} = r_2 - r_c$

By definition:

- $M_1 r_{1c} + M_2 r_{2c} = 0$
- $m_1 r_{1c} + m_2 r_{2c} = 0$
- $m_1 (r_1 - r_c) + m_2 (r_2 - r_c) = 0$

Therefore,

- $\vec{r_c} = \dfrac{m_1 \vec{r_1} + m_2 \vec{r_2}}{m_1 + m_2}$
    
- $${\vec{r_c} = \dfrac{\sum_{i=1}^n m_i r_i}{\sum_{i=1}^n m_i}}$$

---

###  Example Problem
-dia
	![[CM Q.excalidraw]]
Given system of masses:

- $X_{cm} = \dfrac{2m(-3) + m(1) + 2m(6) + 3m(3)}{8m}$
    
- $X_{cm} = \dfrac{-6m + m + 12m + 9m}{8m} = 2$
    
- $Y_{cm} = \dfrac{2m(4) + m(6) + 2m(4) + 3m(0)}{8m}$
    
- $Y_{cm} = \dfrac{8m + 6m + 8m}{8m} = \dfrac{11}{4}$
- $r_{cm} = \left( 2, \dfrac{11}{4} \right)$

---

$m_1 \leftarrow CM \rightarrow m_2$

$\frac{x_1}{x_2} = \frac{m_2}{m_1}$

## **Center of mass of continuous mass distribution**

• If in any object, mass is distributed uniformly over its whole volume or area or length, then CM lies on the line of symmetry of the object. If the object have 2 or more line of symmetry then CM will be at intersection of all line of symmetry.



• For regular object with uniform mass distribution CM will be at the geometric center of object (sphere, cube, etc.)


## **Center of mass of Non-uniform continuous mass distribution**
-dia
	![[CM Q2.excalidraw]]
Taking a small part (dx) of the Non unform rod so it is uniform 
$dm = dx \times \lambda$ where $\lambda = \frac{M}{L}$ and $\sigma = \frac{M}{A}$

$dm = kx dx$

$x_{cm} = \frac{\int x dm}{\int dm}$        (known)

$X_{cm} = \frac{\int x dm}{\int dm} \Rightarrow \frac{\int x \lambda dx}{\int \lambda dx}$

$X_{cm} = \frac{x^2}{2} \cdot \frac{\lambda \int x^2 dx}{\lambda \int dx} = \frac{\frac{x^3}{3}|_0^L}{\frac{x^2}{2}|_0^L} = \frac{L^3 \times 2}{3 \times L^2} = \frac{2L}{3}$

---
## **Additive system**
-dia
	![[Additive_system.excalidraw]]


Mass of rectangle = $\sigma \times A = 4a^2\sigma$ 
Mass of icircle = $\sigma \times A = \pi a^2\sigma$

$X_{cm} = \frac{M_s x_s + M_c x_c}{M_s + M_c} \Rightarrow \frac{4\sigma a^2 \times a + \frac{\pi a^2\sigma}{2} \times 3a}{4\sigma a^2 + \frac{\pi a^2\sigma}{2}}$

$X_{cm} = \frac{(4+3\pi)a}{4+\pi}$

$Y_{cm}$ is found using axis of symmetry clearly it is at distance $a$ from x-axis

$r_{cm} = \left(\frac{4+3\pi}{4+\pi}a, a\right)$

---
### Results

$\lambda_{cm} = \frac{x_1 m_1 + x_2 m_2 + ... + x_n m_n}{m_1 + m_2 + ... + m_n}$

differentiating

$v_{cm} = \frac{v_1 m_1 + v_2 m_2 + ... + v_n m_n}{m_1 + m_2 + ... + m_n}$

differentiating

$a_{cm} = \frac{a_1 m_1 + a_2 m_2 + ... + a_n m_n}{m_1 + m_2 + ... + m_n}$

If external force acting on a system of particles is 0, $a_{cm}$ is 0 and change in velocity of cm is 0

If $\sum F_{ext} = 0$, $a_{cm} = 0$, $\Delta v_{cm} = 0$

& if $v_{cm} = 0$, $F_{ext} = 0$, $\Delta x_{cm} = 0$ No change in position of cm

---

#Q platform moving while man walks on it
-dia
	![[CM Q3.excalidraw]]


$\Delta x_{pg} = +x$ 
$\Delta x_{mp} = -L$ 
$\Delta x_{mp} = \Delta x_{mg} - \Delta x_{pg}$ 
$\Delta x_{mg} = x - L$

$\Delta x_{cm} = \frac{Mx + m(x-L)}{M+m}$ (Change of CM)

**We know $\sum F_{ext} = 0$ so $\Delta x_{cm}$ has to be 0**

$Mx + mx - mL = 0$ $x = \frac{mL}{M+m}$