

## Electric Flux Definition

**Electric flux** is the surface integral of the electric field ($E$). It represents the number of electric field lines passing through a given area.

### Units

- **SI Unit:** $N \cdot m^2 / C$ (Newton-meter squared per Coulomb)
    
- **Other Unit:** Volt-meter
    
- **Alternative:** Gauss (though typically used for magnetic flux, it is noted here in context)
    

---

## Flux for a Uniform Electric Field

When the electric field $\vec{E}$ is **uniform** (constant in magnitude and direction), the integral simplifies to a dot product:

$$\Phi = \int d\phi = \int \vec{E} \cdot d\vec{s} = \vec{E} \cdot \int d\vec{s}$$

$$\Phi = \vec{E} \cdot \vec{S} = E S \cos \theta = (E_{\parallel}) S$$

Where:

- **$E$**: Magnitude of the electric field.
    
- **$S$**: Surface area ($S = \pi R^2$ for a circle).
    
- **$\theta$**: The angle between the **Electric Field** vector and the **Area Vector** (which is perpendicular to the surface).
    

---

## Example Calculation

The diagram shows a circular surface of radius $R$ in a uniform electric field.

**Given:**
![[Pasted image 20260331162836.png]]
- Area ($S$) = $\pi R^2$
    
- The electric field makes an angle of $60^{\circ}$ with the **surface**.
    
- The angle $\theta$ for the formula is measured from the **normal (perpendicular)** to the surface.
    
- Therefore, $\theta = 90^{\circ} - 60^{\circ} = 30^{\circ}$.
    

**Calculation:**

$$\Phi = E \cdot \pi R^2 \cdot \cos 30^{\circ}$$

Since $\cos 30^{\circ} = \frac{\sqrt{3}}{2}$:

$$\Phi = \frac{E \pi R^2 \sqrt{3}}{2}$$

> **Note:** Always be careful to identify if the given angle is with the _surface_ or the _normal_ to the surface. Gauss’s law specifically uses the angle with the normal.











# Gauss theorem

**Definition:**

The surface integral of the electric field ($E$) over a closed surface is always equal to the total charge enclosed by the surface per unit permittivity of free space. This is known as **Gauss's Law**.

### Mathematical Representation

The law is expressed by the following formula:

$$\Phi = \oint \vec{E}_{net} \cdot d\vec{s} = \frac{Q_{in}}{\varepsilon_0} = \frac{Q_1 + Q_2 + Q_3}{\varepsilon_{0}} \ (include\ signs)$$

### Diagram Components

![[Pasted image 20260331162225.png]]

- **Enclosed Charges ($Q_{in}$):** $Q_1$, $Q_2$, and $Q_3$. These are the only charges that contribute to the net flux through the surface.
    
- **External Charge:** $Q_4$. This charge is located outside the Gaussian surface and does not contribute to the total enclosed charge ($Q_{in}$), though it does contribute to the local electric field $\vec{E}$ at points on the surface.

This image illustrates an application of **Gauss's Law** to find the electric flux through a single face of a cube when a charge is placed at its center.

---

### **Problem Description**

A point charge $Q$ is placed at the **center** of a cube. Because the cube is a closed surface and the charge is perfectly centered, the electric field lines originate from the charge and pass through all six faces of the cube with perfect symmetry.

### **Mathematical Derivation**

1. **Total Net Flux ($\Phi_{net}$):**
    
    According to Gauss's Law, the total flux passing through any closed surface is equal to the enclosed charge divided by the permittivity of free space ($\varepsilon_0$):
    
    $$\Phi_{net} = \frac{Q}{\varepsilon_0}$$
    
2. **Symmetry Argument:**
    
    Since the charge is at the geometric center, the flux is distributed equally across all **6 faces** of the cube.
    
3. **Relation between Total Flux and Single Face Flux:**
    
    The total flux is the sum of the flux through each of the six faces:
    $$\Phi_{net} = \frac{Q}{\varepsilon_0} = 6\phi$$
**Final Formula for Flux through one face:**
    Solving for $\phi$, we get:
    
    $$\phi = \frac{Q}{6\varepsilon_0}$$