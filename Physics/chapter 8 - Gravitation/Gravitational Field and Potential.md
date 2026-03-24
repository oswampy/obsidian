### Gravitational Field Due to Continuous Mass Distribution
#Derivation 

$dI = Rd\theta$

$λ = \frac{dm}{dI} \Rightarrow \frac{λ}{2πc}$

$dm = m \times \frac{Rd\theta}{2πR} \Rightarrow \frac{m d\theta}{2π}$

$dE = \frac{Gm dm}{R^2}$

Some  $\vec{E}$  fields to remember:

### i) Ring on axis

$$E = \frac{Gm x}{(R^2 + x^2)^{3/2}}$$

### ii) Disc on axis

$$E = \frac{2Gm x}{R^2}\left[\frac{1}{R^2} - \frac{1}{\sqrt{x^2+R^2}}\right]$$

### iii) For uniform shell

For $r > R \Rightarrow E = \frac{Gm}{R^2}$

For $r = R \Rightarrow E = 0$

For $r < R \Rightarrow E = \frac{Gm}{z^2}$

### iv) For spherical solid sphere

$$E = \frac{Gm_A(z > R)}{R^2}$$

$$E_I = \frac{Gm(4z > R)}{z^2}$$

---

## Gravitational Potential

The gravitational potential at a point in the gravitational field of a body is defined as the amount of work done by an external agent in bringing a body of unit mass from infinity to that point slowly.

For a mass $m$ at distance $r$ from unit mass: $$V = -\frac{Gm}{r}$$

### Gravitational Potential:

**1) Solid sphere** $$V = -\frac{Gm}{r}, \quad r > R$$
$$V = -\frac{3Gm}{2R}, \quad r = 0$$
$$V = -\frac{Gm}{2R^2}\left[\frac{3R^2 - r^2}{2}\right], \quad r < R$$

**2) Hollow sphere**

$$V = -\frac{Gm}{r}, \quad r > R$$

$$V = -\frac{Gm}{R}, \quad r < R$$
### Potential Energy

$U(r) = -\frac{GMm}{2R^3}(3R^2 - r^2)$
Remember:


| Case                             | Gravitational Field **E** | Nature of **E**   | Gravitational Potential **V** | Nature of **V**      |
| -------------------------------- | ------------------------- | ----------------- | ----------------------------- | -------------------- |
| **Outside solid sphere** (r > R) | `GM / r²`                 | decreases as 1/r² | `−GM / r`                     | increases (less −ve) |
| **Inside solid sphere** (r < R)  | `(GM / R³) r`             | ∝ r (linear)      | `−(GM / 2R³)(3R² − r²)`       | minimum at centre    |
| **Outside hollow shell** (r > R) | `GM / r²`                 | decreases as 1/r² | `−GM / r`                     | increases            |
| **Inside hollow shell** (r < R)  | `0`                       | zero everywhere   | `−GM / R`                     | constant             |
| **At centre** (r = 0)            | `0`                       | zero              | `−3GM / 2R`                   | minimum              |
| **At surface** (r = R)           | `GM / R²`                 | maximum           | `−GM / R`                     | continuous           |

---

## Relation between $\vec{E}$ and Potential 
For a unit mass:
	$\vec{E} = \vec{F} \quad (\vec{F} = m\vec{E}) \quad \text{(i)}$
	$E = V$ (E=MU)
	$dW =  Fdr$ 
	$dE = -f dr \quad \text{(ii)}$  
	$dV = -E dr \quad \text{(from (i) and (ii))}$ $$\vec{E} = -\frac{dV}{dr}$$ OR $$\Delta V = -\int \vec{E} dr$$
 
 If $$\vec{E} = -3\pi^2uy + 7u^2 + x$$ $$E_x = -\frac{\partial u}{\partial x} = -(-6\pi uy + 22y) - (6\pi y + 1)$$ Hence, gravitational field at any point is equal to the negative gradient of potential